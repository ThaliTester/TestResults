#### Test 62509094058a2d4_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 3978): MountEmulatedStorage()
E/Zygote  ( 3978): v2
I/SELinux ( 3978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3978): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/libpersona( 3978): KNOX_SDCARD checking this for 10032
I/libpersona( 3978): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3978 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1573:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/TimaKeyStoreProvider( 3978): TimaSignature is unavailable
D/ActivityThread( 3978): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1573/cgroup.procs: No such file or directory
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
E/SQLiteLog( 3771): (283) recovered 63 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ContextImpl( 1979): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1017): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/ActivityManager( 1017): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
D/SecUISvc( 1979): Service started flags 0 startId 1
D/SecUISvc( 1979): Thread created.
D/AndroidHttpClient( 3393): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/AndroidHttpClient( 3393): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 3393): Thread-512(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3393): Thread-512(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3393): Thread-512(ApacheHTTPLog):isShipBuild true
I/System.out( 3393): Thread-512(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3393): Thread-512(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4006): MountEmulatedStorage()
E/Zygote  ( 4006): v2
I/libpersona( 4006): KNOX_SDCARD checking this for 10028
I/libpersona( 4006): KNOX_SDCARD not a persona
I/SELinux ( 4006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4006 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/SELinux ( 4006): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4006): TimaSignature is unavailable
D/ActivityThread( 4006): Added TimaKeyStore provider
E/Zygote  ( 4021): MountEmulatedStorage()
E/Zygote  ( 4021): v2
I/libpersona( 4021): KNOX_SDCARD checking this for 10033
I/libpersona( 4021): KNOX_SDCARD not a persona
I/SELinux ( 4021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4021): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4021 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3246:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
D/AndroidRuntime( 3998): 
D/AndroidRuntime( 3998): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3998): CheckJNI is OFF
D/AndroidRuntime( 3998): readGMSProperty: start
D/AndroidRuntime( 3998): readGMSProperty: already setted!!
D/AndroidRuntime( 3998): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3998): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3998): readGMSProperty: end
D/AndroidRuntime( 3998): addProductProperty: start
D/TimaKeyStoreProvider( 4021): TimaSignature is unavailable
D/ActivityThread( 4021): Added TimaKeyStore provider
D/TimaService( 1017): TIMA: in getTimaVersion
D/TimaService( 1017): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1017): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1017): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1017): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1017): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
I/ActivityManager( 1017): Killing 3307:com.policydm/1000 (adj 15): empty #31
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3246/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3307/cgroup.procs: No such file or directory
E/AffinityControl( 3998): AffinityControl: registerfunction enter
D/AndroidRuntime( 3998): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3889): Resource data:2131165186
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ResourcesManager( 3889): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3889): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
D/Launcher.HomeView( 1488): onPause
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1488
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : -2122120936
D/AndroidRuntime( 3998): Shutting down VM
D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 4049): MountEmulatedStorage()
I/libpersona( 4049): KNOX_SDCARD checking this for 10155
E/Zygote  ( 4049): v2
I/libpersona( 4049): KNOX_SDCARD not a persona
I/SELinux ( 4049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4049 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4049): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1488): updateVisibility : ActivityRecord{289cae6a token=android.os.BinderProxy@2a4bf343 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 4049): TimaSignature is unavailable
D/ActivityThread( 4049): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1488): onStop
V/ActivityThread( 1488): updateVisibility : ActivityRecord{289cae6a token=android.os.BinderProxy@2a4bf343 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1017): [SO] activate (ident=0xb8f4ff80, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1017): unregisterListener ::   
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb90bd5c8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/QSEECOMAPI: ( 1017): Loaded image: APP id = 10
I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1017): ctx = 0xb90db740, comm = 0xb8fc6168, sendmsg = 0xa0bbe000, recvmsg = 0xa0bbe440
I/TZ_init: ( 1017): TZ_init: sending initialization request...
E/TZ_init: ( 1017): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1017): trustlet initialization failed
I/TZ_init: ( 1017): TZ_init_START...
I/DBG_DM  ( 3208): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
I/TZ_init: ( 1017): TZ_init_with_data: sending initialization request...
I/TZ_init: ( 1017): TZ_init: successful initialization
D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 10
E/TLC_TZ_KEYSTORE: ( 1017): Count : 1, Ret : 0
I/AMMetaDataParserService( 3889): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
W/ResourcesManager( 4021): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4021): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/File    ( 3771): fail readDirectory() errno=2
W/art     ( 3998): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/System.out( 3393): Thread-512 calls detatch()
,E/SMD     (  287): DCD OFF
,I/Gmail   ( 3771): notifyAccountChanged
,D/Launcher( 1488): onTrimMemory. Level: 20
,W/ResourcesManager( 4021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/art     ( 3859): Suspending all threads took: 14.529ms
,I/Gmail   ( 3771): getAccountsCursor
,I/WebViewFactory( 4049): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 4021): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4021): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4021): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorService( 1017): [SO] 0.153 0.402 10.132
,D/SensorService( 1017): [SO] [100 -> 255]
,I/LibraryLoader( 4049): Time to load native libraries: 2 ms (timestamps 3942-3944)
I/LibraryLoader( 4049): Expected native library version number "",actual native library version number ""
,I/ActivityManager( 1017): Killing 3261:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3889): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3771): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4049): Binding Chromium to main looper Looper (main, tid 1) {3266e813}
,I/LibraryLoader( 4049): Expected native library version number "",actual native library version number ""
,I/chromium( 4049): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Gmail   ( 3771): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 3947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,I/BrowserStartupController( 4049): Initializing chromium process, singleProcess=true
,W/art     ( 4049): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4049): ApplicationContext is null in ApplicationStatus
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131034113
,I/Gmail   ( 3771): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3771): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 3889): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,W/libprocessgroup( 1017): failed to open /acct/uid_10086/pid_3261/cgroup.procs: No such file or directory
,W/chromium( 4049): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4049): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 4049): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3889): took 2.326354ms for 0*0 texture 0
,I/Adreno-EGL( 4049): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4049): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4049): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4049): Local Branch: 
I/Adreno-EGL( 4049): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4049): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4049):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/GFX generate_partition_tables( 3889): took 6.364895ms for 0*0 texture 0
,I/GFX raster( 3889): took 9.948696ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b691d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b694b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4084): MountEmulatedStorage()
E/Zygote  ( 4084): v2
I/libpersona( 4084): KNOX_SDCARD checking this for 1000
I/libpersona( 4084): KNOX_SDCARD not a persona
,I/SELinux ( 4084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 4084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Babel   ( 3932): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3932): MmsConfig.loadMmsSettings
I/Babel   ( 3932): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3932): MmsConfig.loadFromDatabase
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,D/TimaKeyStoreProvider( 4084): TimaSignature is unavailable
,E/Babel   ( 3932): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3932): MmsConfig.loadFromResources
,E/Babel   ( 3932): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3932): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityThread( 4084): Added TimaKeyStore provider
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 3932): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.811302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b691d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b78040 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4084): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/SEAMService( 1017):  hashset_to_int_array returning null
,W/ContextImpl( 4084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,W/SEAMService( 1017):  hashset_to_int_array returning null
,E/SQLiteLog( 3947): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3947): (284) automatic index on seams_container_info(sp_id)
,W/SEAMService( 1017):  hashset_to_int_array returning null
,I/ActivityManager( 1017): Killing 3329:com.dropbox.android/u0a92 (adj 15): empty #31
,I/F_PHONE ( 4084): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4084): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1017): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
I/Babel_StickerModule( 3932): App launched.
,D/Finsky  ( 4006): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/F_PHONE ( 4084): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4084): default registerAction()
,I/F_PHONE ( 4084): [[com.sec.bcservice]] sendPendingMessage()
,W/ResourcesManager( 3978): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10092/pid_3329/cgroup.procs: No such file or directory
,W/ResourcesManager( 3978): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3978): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3978): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/chromium( 4049): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
V/Babel   ( 3932): babel boot account: SMS
,W/Babel   ( 3932): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3932): java.lang.Exception
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3932): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3932): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3932): 	at ckh.a(SourceFile:67)
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3932): 	at bhn.a(SourceFile:301)
W/Babel   ( 3932): 	at bhn.a(SourceFile:137)
W/Babel   ( 3932): 	at bhn.a(SourceFile:126)
W/Babel   ( 3932): 	at bhn.a(SourceFile:159)
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3932): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3932): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3932): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3932): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3932): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3932): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3932): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3932): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3932): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3932): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,I/Gmail   ( 3771): getAccountsCursor
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/Babel   ( 3932): java.lang.Exception
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3932): 	at aes.a(SourceFile:145)
W/Babel   ( 3932): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3932): 	at ckh.a(SourceFile:67)
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3932): 	at bhn.a(SourceFile:301)
W/Babel   ( 3932): 	at bhn.a(SourceFile:137)
W/Babel   ( 3932): 	at bhn.a(SourceFile:126)
W/Babel   ( 3932): 	at bhn.a(SourceFile:159)
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3932): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3932): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3932): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3932): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3932): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3932): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3932): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3932): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3932): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3889): took 2.246823ms for 0*0 texture 0
,W/art     ( 4049): Attempt to remove local handle scope entry from IRT, ignoring
,I/GFX generate_partition_tables( 3889): took 7.364063ms for 0*0 texture 0
,I/GFX raster( 3889): took 10.546251ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74b68 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.606771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b721d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b722a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/AwContents( 4049): onDetachedFromWindow called when already detached. Ignoring
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.845105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b775f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b776c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/PhoneWindow( 4049): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 4049): *FMB* installDecor flags : -2139027200
,I/AMMetaDataParserService( 3889): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/SystemWebViewEngine( 4049): CordovaWebView is running on device made by: samsung
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.735469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b702d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b703b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.861094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b71270 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b71338 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.522135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b761c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b76288 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131034113
,I/AMMetaDataParserService( 3889): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.816562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b691d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 36965(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 14.055ms total 185.439ms
,W/art     ( 4049): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/art     ( 4049): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.818021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b691d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3889): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3932): babel boot account: thalitester@gmail.com
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.598073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,I/AMMetaDataParserService( 3889): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/Babel   ( 3932): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,I/Process ( 4021): Sending signal. PID: 4021 SIG: 9
,W/Babel   ( 3932): java.lang.Exception
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3932): 	at aes.a(SourceFile:145)
W/Babel   ( 3932): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3932): 	at ckh.a(SourceFile:67)
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3932): 	at bhn.a(SourceFile:301)
W/Babel   ( 3932): 	at bhn.a(SourceFile:137)
W/Babel   ( 3932): 	at bhn.a(SourceFile:126)
W/Babel   ( 3932): 	at bhn.a(SourceFile:159)
W/Babel   ( 3932): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3932): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3932): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3932): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3932): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3932): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3932): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3932): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3932): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3932): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/OpenGLRenderer( 4049): Render dirty regions requested: true
,I/DBG_DM  ( 3208): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/PhoneWindow( 4049): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 4049): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 4049
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4049): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4049): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4049): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 4049): Enabling debug mode 0
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 4021)(adj 0) has died(74,1157)
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4151): MountEmulatedStorage(),
E/Zygote  ( 4151): v2
I/libpersona( 4151): KNOX_SDCARD checking this for 10034
I/libpersona( 4151): KNOX_SDCARD not a persona
I/System.out( 3859): INFO:Resource not found:/Common.properties Using default values
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4151 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 4151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/SSRM:n  ( 1017): SIOP:: AP = 390
,D/TimaKeyStoreProvider( 4151): TimaSignature is unavailable
,D/ActivityThread( 4151): Added TimaKeyStore provider
D/Finsky  ( 4006): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1186): Icon Only
,D/PanelView( 1186): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s311ms
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{100a8574 u0 com.test.thalitest/.MainActivity t12} time:44957
W/ActivityManager( 1017): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 4049): Timeline: Activity_idle id: android.os.BinderProxy@bef7bac time:44966
,I/SamsungIME( 1845): getCurrentCandidateView
,W/Settings( 4006): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4006): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.610573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b721d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,I/SecDataIO(  256): Write to block
,I/AMMetaDataParserService( 3889): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.822240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b775f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ContextImpl( 2655): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/Process ( 2655): Sending signal. PID: 2655 SIG: 9
,E/lowmemorykiller(  254): Error writing /proc/2655/oom_score_adj; errno=22
,I/DBG_DM  ( 3208): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3208): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3208): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3208): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.631510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b702d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.683854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b71270 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/Zygote  ( 4175): MountEmulatedStorage()
E/Zygote  ( 4175): v2
I/libpersona( 4175): KNOX_SDCARD checking this for 1000
I/libpersona( 4175): KNOX_SDCARD not a persona
,I/SELinux ( 4175): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,I/SELinux ( 4175): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4175): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4175 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
W/QCamera2Factory(  282): getCameraInfo: X
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (-2/8)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4185 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/SamsungIME( 1845): Dismiss ExpandCandiate
E/Zygote  ( 4185): MountEmulatedStorage()
I/libpersona( 4185): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4185): v2
I/libpersona( 4185): KNOX_SDCARD not a persona
I/SELinux ( 4185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4185): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Process com.sec.android.app.sysscope (pid 2655)(adj 0) has died(58,1165),
,I/art     (  302): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 902us total 27.562ms,
,W/VideoCapabilities( 3932): Unrecognized profile 2130706433 for video/avc
,W/BindingManager( 4049): Cannot call determinedVisibility() - never saw a connection for the pid: 4049
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.564323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b761c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b74770 counterpartCT=4 counterpartW=96 counterparth=96
W/AudioCapabilities( 3932): Unsupported mime audio/evrc
,W/AudioCapabilities( 3932): Unsupported mime audio/qcelp
I/AMMetaDataParserService( 3889): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/TimaKeyStoreProvider( 4185): TimaSignature is unavailable
D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
D/ActivityThread( 4185): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3889): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3889): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131034112
,D/TimaKeyStoreProvider( 4175): TimaSignature is unavailable
,D/ActivityThread( 4175): Added TimaKeyStore provider
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 830us total 24.930ms
,I/AMMetaDataParserService( 3889): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 1.847603ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b721d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b57fd8 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3932): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3932): Unsupported mime audio/mpeg-L2
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 21.776ms
,D/Volley  ( 4006): [586] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1017): Killing 3417:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,D/Volley  ( 4006): [593] DiskBasedCache.clear: Cache cleared.
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Ads     ( 4006): Skipping gmscore version check
,I/AMMetaDataParserService( 3889): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 4049): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup( 1017): failed to open /acct/uid_10092/pid_3417/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 4006): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 3932): Unsupported mime audio/x-ms-wma
,D/Finsky  ( 4006): [1] Libraries$2.run: Finished loading 1 libraries.
,W/AudioCapabilities( 3932): Unsupported mime audio/x-ima
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.615312ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b721d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b57fd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/FileApkUtils( 2067): Optimizing (staging complete)
,D/FileApkUtils( 2067): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,I/art     ( 2067): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory,
,W/AudioCapabilities( 3932): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3932): Unsupported mime audio/evrc
,D/DexOptUtils( 2067): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
D/DexOptUtils( 2067): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 2067): Instantiating DexClassLoader to force creation of odex.
,D/DexOptUtils( 2067): Primary ABI of odexing process is armeabi-v7a
,D/Finsky  ( 4006): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,W/VideoCapabilities( 3932): Unsupported mime video/wvc1
,W/VideoCapabilities( 3932): Unsupported mime video/x-ms-wmv
,I/SamsungIME( 1845): getDebugLevel  : 0x4f4c
,I/DBG_POLICYDM( 4185): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4185): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4185): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4185): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/dex2oat ( 4218): ----------------------------------------------------
I/dex2oat ( 4218): <SS>: S T A R T I N G . . .
I/dex2oat ( 4218): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 4218): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=45 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/Finsky  ( 4006): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3889): took 0.645521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb88d18d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b56b18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/VideoCapabilities( 3932): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3932): Unsupported mime video/wvc1
,W/VideoCapabilities( 3932): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3932): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3932): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3932): Unsupported mime video/mp43
,W/VideoCapabilities( 3932): Unsupported mime video/sorenson
,W/VideoCapabilities( 3932): Unsupported mime video/mp4v-esdp
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.623906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb87a3c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b691d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4226 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4226): MountEmulatedStorage()
E/Zygote  ( 4226): v2
I/libpersona( 4226): KNOX_SDCARD checking this for 1000
I/libpersona( 4226): KNOX_SDCARD not a persona
,I/SELinux ( 4226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4226): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/InstanceID/Rpc( 2067): Found 10012
I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/TimaKeyStoreProvider( 4226): TimaSignature is unavailable
D/ActivityThread( 4226): Added TimaKeyStore provider
,I/VideoCapabilities( 3932): Unsupported profile 4 for video/mp4v-es
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager( 1017): Killing 3438:com.fmm.dm/1000 (adj 15): empty #31
,I/SamsungIME( 1845): getDebugLevel  : 0x4f4c
D/jxcore_app_log( 4049): JniHelper::setJavaVM(0xb879c450), pthread_self() = -1194573952
,I/DBG_DM  ( 3208): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131034113
I/AMMetaDataParserService( 3889): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23ce66b added. We now have 1 listener(s)
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.807344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b57a30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b57fd8 counterpartCT=4 counterpartW=96 counterparth=96
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/DBG_DM  ( 3208): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
I/DBG_DM  ( 3208): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4049): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4049): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4049): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4049): setHandshakeRequired: true -> false
I/DBG_DM  ( 3208): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3788a586 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4049): addListener: New listener added - the number of listeners is now 1
I/SamsungIME( 1845): KeybaordView init() : load resources
,I/DBG_POLICYDM( 4185): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 4185): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4049): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4049): setScanMode: 1 -> 2
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
I/AMMetaDataParserService( 3889): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2688): Disconnected process message: 10
,I/DBG_DM  ( 3208): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4049): bind: Binding a new listener
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3438/cgroup.procs: No such file or directory
,D/KnoxSetupWizardDbHelper( 4226): dbMigrationFlag : false
,I/DBG_DM  ( 3208): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 3
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4049): initialize: My bluetooth address is 7C:F9:0E:37:96:AB,
,I/DBG_DM  ( 3208): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2,
,I/DBG_DM  ( 3208): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220],
,I/DBG_DM  ( 3208): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ShortcutReceiver( 4226):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.851510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b57a30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b56b18 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3208): [com.wssyncmldm.llIIllllIIlllIIIIlll(1140/handleMessage)] 
,I/DBG_DM  ( 3208): [com.wssyncmldm.XDMService(685/llIIlIlIIIllIIIIIllI)] 
,V/io.jxcore.node.ConnectivityMonitor( 4049): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 4049):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 4049):     - is Bluetooth LE multiple advertisement supported: SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 4049):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4049):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4049):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 4049):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 4049):     - active network type is Wi-Fi: true
,D/io.jxcore.node.JXcoreExtension( 4049): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 4049): start: OK
,I/AMMetaDataParserService( 3889): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Zygote  ( 4248): MountEmulatedStorage()
I/libpersona( 4248): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4248): v2
I/libpersona( 4248): KNOX_SDCARD not a persona
I/SELinux ( 4248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4248 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3281:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/SELinux ( 4248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4248): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
V/io.jxcore.node.ConnectivityMonitor( 4049): updateConnectivityInfo: No relevant state changes
V/io.jxcore.node.ConnectivityMonitor( 4049): updateConnectivityInfo: No relevant state changes
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,I/chromium( 4049): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SamsungIME( 1845): getCurrentKeyboard
I/SamsungIME( 1845): getTextKeyboard
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 4248): TimaSignature is unavailable
,D/ActivityThread( 4248): Added TimaKeyStore provider
,D/SamsungIME( 1845): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/KnoxShortcutUtil( 4226): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4226):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 4226):  shortcut migration not required 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4267): MountEmulatedStorage()
I/libpersona( 4267): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 4267): v2
I/libpersona( 4267): KNOX_SDCARD not a persona
,I/SELinux ( 4267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 4267): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX raster( 3889): took 0.607813ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b691d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b57fd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3208): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/AMMetaDataParserService( 3889): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4267 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 3456:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/DBG_DM  ( 3208): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3208): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3208): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3208): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3208): [com.wssyncmldm.ui.XUIFotaPostponeActivity(501/llIIIIlllllIIllIIllI)] 
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4267): TimaSignature is unavailable
,I/GFX raster( 3889): took 0.780052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b721d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b56b18 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 4267): Added TimaKeyStore provider
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_3281/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_3456/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/AMMetaDataParserService( 3889): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 4248): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4248): [PushClientApplication] Push log off : This is Ship build version
,I/DBG_DM  ( 3208): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,W/art     ( 1845): Suspending all threads took: 66.923ms
,E/SPPClientService( 4248): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3208): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/SPPClientService( 4248): PushLog.txt file is not deleted.
,D/SPPClientService( 4248): PushLog.txt file is not deleted.
D/SPPClientService( 4248): ============PushLog. stop!
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 1.010624ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b3c390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b57fd8 counterpartCT=4 counterpartW=96 counterparth=96
,E/KnoxSetupWizardClient( 4267): isShipMode : 1
I/KnoxSetupWizardClient( 4267): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3889): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4185): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/BootCompletedReceiver( 2067): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.,
,D/BootCompletedReceiver( 2067): Got an BootCompleted event.
D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,I/DBG_POLICYDM( 4185): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
W/ResourcesManager( 1186): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/GCM     ( 2067): COMPAT: Multi user not supported
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 4185): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,D/BootCompletedReceiver( 2067): Will NOT schedule AdAttestation signal task because it's disabled.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1856): COMPAT: Multi user not supported
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.809375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb87a3c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b56b18 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 2067): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/KnoxNotification( 1186): ----- inflateViews : modified publicViewLocal -----
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/KnoxNotification( 1186): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1186): PersonaID is invalid or persona doesn't exists. : 0
I/libpersona( 4297): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4297): MountEmulatedStorage()
I/libpersona( 4297): KNOX_SDCARD not a persona
E/Zygote  ( 4297): v2
I/ActivityManager( 1017): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4297 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 4297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4297): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 1186): isKioskContainerExistOnDevice
D/PersonaManager( 1186): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1186): Icon Only
I/StatusBar( 1186): Icon Only
D/PanelView( 1186): There is/are notification(s) 
D/PanelView( 1186): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1186): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1186): Icon Only
I/StatusBar( 1186): Icon Only
D/PanelView( 1186): There is/are notification(s) 
D/PanelView( 1186): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 4297): TimaSignature is unavailable
D/ActivityThread( 4297): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/PanelView( 1186): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.688177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b57fd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b56b18 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/SQLiteLog( 3932): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/System.err( 4267): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4267): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4267): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4267): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4267): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4267): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4267): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/Zygote  ( 4314): MountEmulatedStorage(),
E/Zygote  ( 4314): v2
I/libpersona( 4314): KNOX_SDCARD checking this for 10041
I/libpersona( 4314): KNOX_SDCARD not a persona
,I/SELinux ( 4314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4314 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3498:com.fmm.ds/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 4185): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] ,
I/DBG_POLICYDM( 4185): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4185): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/SELinux ( 4314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4314): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_POLICYDM( 4185): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,I/DBG_POLICYDM( 4185): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/15/13:15:57
,E/SQLiteLog( 3932): (284) automatic index on conversation_participants_view(conversation_id)
I/DBG_POLICYDM( 4185): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,E/SMD     (  287): DCD OFF
,D/TimaKeyStoreProvider( 4314): TimaSignature is unavailable
,D/ActivityThread( 4314): Added TimaKeyStore provider
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.525417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b56b18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b72190 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3932): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4185): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4185): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,I/AMMetaDataParserService( 3889): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3498/cgroup.procs: No such file or directory
,I/CheckinService( 2067): Disabling old GoogleServicesFramework version
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
I/DBG_POLICYDM( 4185): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4185): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,E/SQLiteLog( 3932): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4185): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4185): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4185): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4185): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889,): Resource data:2131165203
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ResourcesManager( 3889): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog( 3932): (284) automatic index on conversation_participants_view(conversation_id)
,D/SystemUpdateService( 2067): onCreate
,I/AMMetaDataParserService( 3889): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1017): Killing 3514:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/GFX construct_block_size_descriptor_2d second part( 3889): took 3.126615ms for 0*0 texture 0
,I/SA      ( 4314): [SSP] onCreated
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{21083181 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,I/GFX generate_partition_tables( 3889): took 10.453647ms for 0*0 texture 0
,I/GFX raster( 3889): took 14.508178ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b53e20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b55440 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3889): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/SA      ( 4314): [TPM] There is no property file
,I/SA      ( 4314): [SCU] isHaveSA() - false
,I/SA      ( 4314): [TPM] getModelProperty : null
I/SA      ( 4314): [TPM] getCSCProperty : null
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/SA      ( 4314): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4314): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4314): [DM] TFT FEATURE: false
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.938230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4b8d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 2067): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SA      ( 4314): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4314): [DM] init START
,I/AMMetaDataParserService( 3889): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/SA      ( 4314): [DM] This device is not a Vodafone
,I/DBG_POLICYDM( 4185): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.966923ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4b8d0 counterpartCT=4 counterpartW=96 counterparth=96
,V/AuthZen ( 2067): Handling intent: android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4185): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/AMMetaDataParserService( 3889): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/libprocessgroup( 1017): failed to open /acct/uid_10060/pid_3514/cgroup.procs: No such file or directory
,W/ResourceType( 4314): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4314): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4314): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4314): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4314): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,D/AuthZenEventHandler( 2067): Handling event: android.intent.action.BOOT_COMPLETED
W/ResourceType( 4314): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4314): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4314): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.770781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26c60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b52e98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/ResourceType( 4314): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75),
,W/ResourceType( 4314): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4314): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4314): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,I/SA      ( 4314): [SCU] isHaveSA() - false
I/SA      ( 4314): support phone number id : false
I/SA      ( 4314): [DM] Supports Ref Jpn : true
,I/SA      ( 4314): [DM] init END
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/CheckinService( 2067): Checking schedule, now: 1458044158212 next: 1458246240395
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CheckinService( 2067): active receiver: disabled
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/SA      ( 4314): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4314): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/GFX raster( 3889): took 0.597865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b52e98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b55570 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3889): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4314): [OR] onReceive END
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4348 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 4348): MountEmulatedStorage(),
E/Zygote  ( 4348): v2
I/libpersona( 4348): KNOX_SDCARD checking this for 10042
I/libpersona( 4348): KNOX_SDCARD not a persona
,I/SELinux ( 4348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4348): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/SA      ( 4314): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4314): [ODM] queryOpenData(key= GEO_IP )
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.660521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b52e98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4b8d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4348): TimaSignature is unavailable
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityThread( 4348): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,I/SystemUpdateService( 2067): cancelUpdate (empty URL)
I/SystemUpdateService( 2067): active receiver: disabled
,I/SA      ( 4314): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4314): [LBE] REF_JPN : true
,I/SA      ( 4314): [BDC] create
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2067): Using Auth Proxy for data requests.
,I/GAV2    ( 3771): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 4314): [DBMV2] getEmailID
,I/SA      ( 4314): [DBMV2] getDataV02ForItems
I/SA      ( 4314): [SSP] query invoked
,I/SA      ( 4314): [SCU] get signed id from samsung account2.0 DB.
,W/ResourcesManager( 4348): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4314): [SCU] get signed id from samsung account1.0 DB.
,I/AMMetaDataParserService( 3889): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4314): [BDC] destroy
,I/ActivityManager( 1017): Killing 3549:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/GCoreUlr( 1856): DispatchingService.onCreate()
,D/EnterpriseController(  277): uids 10012
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,D/GCM     ( 1856): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED,
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_3549/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,E/BaseAppContext( 2067): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,W/jxcore-log( 4049): Initializing JXcore engine
W/jxcore-log( 4049): JXcore engine is ready
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/CalendarProvider2( 4348): CalendarProvider2.onCreate() called
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1856): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 3889): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.858854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26458 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b69390 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCM     ( 1856): GCM config loaded
,E/audit   ( 1942): type=1400 msg=audit(1458044158.745:205): avc:  denied  { ioctl } for  pid=4247 comm="Thread-614" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1942):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1942): type=1300 msg=audit(1458044158.745:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b00a8f8 items=0 ppid=302 ppcomm=main pid=4247 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-614" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1942): type=1320 msg=audit(1458044158.745:205): 
,W/jxcore-log( 4049): Starting JXcore engine
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AuthZen ( 2067): Fetching signing key...
,I/AuthZen ( 2067): Signing key fetched successfully!
,D/PowerManagerService( 1017): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1017): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1017): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 1856): Explicit concurrent mark sweep GC freed 15605(1014KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 12MB/21MB, paused 1.218ms total 67.238ms
,W/jxcore-log( 4049): Platform android
W/jxcore-log( 4049): 
,W/jxcore-log( 4049): Process ARCH arm
W/jxcore-log( 4049): 
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3889): took 2.299792ms for 0*0 texture 0
,I/art     ( 1680): Explicit concurrent mark sweep GC freed 5021(207KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.028ms total 42.995ms
,D/PowerManagerService( 1017): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 19 -> 19
D/lights  ( 1017): lcd : 19 +
D/DisplayPowerController( 1017): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/SQLiteConnectionPool( 1680): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1017): lcd : 19 -
,D/DisplayPowerController( 1017): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1017): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/BaseAppContext( 2067): Using Auth Proxy for data requests.
,I/GFX generate_partition_tables( 3889): took 8.759374ms for 0*0 texture 0
,I/GFX raster( 3889): took 12.064167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b69390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b79d48 counterpartCT=4 counterpartW=96 counterparth=96
,D/a       ( 2067): Opening database auth.proximity.permit_store...
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1845): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/AuthZenTransactionCache( 2067): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2067): Clearing transaction cache
,D/SystemUpdateService( 2067): onDestroy
,I/AMMetaDataParserService( 3889): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/Auth    ( 1856): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 3572:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/GCoreUlr( 1856): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.615885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b79d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b51cd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.640989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b75040 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3572/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3889): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.697604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b68038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b680e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 40365(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 26MB/40MB, paused 3.379ms total 203.108ms
,I/GCoreUlr( 1856): Unbound from all location providers
,I/GCoreUlr( 1856): Place inference reporting - stopped
,I/iu.UploadsManager( 2067): End new media; added: 0, uploading: 0, time: 435 ms
,V/GLSActivity( 1856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 2067): Aggregate from 1458042178098 (log), 1458042178098 (data)
,W/GCoreFlp( 1856): No location to return for getLastLocation()
,W/FusedLocationProvider( 1856): location=null
,I/GCoreUlr( 1856): DispatchingService.onDestroy()
,I/GCoreUlr( 1856): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1856): Unbound from all location providers
I/GCoreUlr( 1856): Place inference reporting - stopped
,W/GCoreFlp( 1856): No location to return for getLastLocation()
,W/FusedLocationProvider( 1856): location=null
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.719323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b518d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b6bf30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/jxcore-log( 4049): JXcore Cordova bridge is ready!
I/jxcore-log( 4049): 
,W/jxcore-log( 4049): JXcore engine is started
,I/ActivityManager( 1017): Killing 3352:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/org.thaliproject.p2p.ThaliPermissions( 4049): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,D/PersistentNotificationBroadcastReceiver( 1856): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/AMMetaDataParserService( 3889): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.690261ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26458 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b52678 counterpartCT=4 counterpartW=96 counterparth=96
,I/chromium( 4049): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/jxcore  ( 4049): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4049): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.647969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b69390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b753a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/chromium( 4049): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 4049): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 4049
I/AMMetaDataParserService( 3889): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/StrictMode( 4297): StrictMode policy violation; ~duration=1641 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4297): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4297): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4297): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4297): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4297): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4297): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1592 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4297): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4297): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4297): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4297): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4297): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1383 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4297): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4297): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4297): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4297): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4297): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4297): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1380 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4297): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4297): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4297): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4297): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Inst,rumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1379 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4297): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4297): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4297): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4297): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1377 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4297): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4297): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4297): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4297): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4297): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4297): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4297): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4297): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4297): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4297): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4297): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4297): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1372 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4297): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4297): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4297): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4297): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4297): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4297): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4297): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4297): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4297): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4297): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4297): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4297): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4297): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1320 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4297): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4297): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4297): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4297): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4297): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4297): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4297): StrictMode policy violation; ~duration=1319 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4297): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4297): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4297): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4297): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4297): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4297): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4297): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4297): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4297): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4297): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.619479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b79d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b668c8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3889): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (172 us)
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.686302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d27270 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3889): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.629115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b68038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ed4bc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/ActivityManager( 1017): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/PluginManager( 4049): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 83ms. Plugin should use CordovaInterface.getThreadPool().
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
W/libprocessgroup( 1017): failed to open /acct/uid_10009/pid_3352/cgroup.procs: No such file or directory
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4405): MountEmulatedStorage(),
,I/libpersona( 4405): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4405): v2
I/libpersona( 4405): KNOX_SDCARD not a persona
,I/SELinux ( 4405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4405 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1017): [SO] activate (ident=0xb90bd5c8, enabled=0)
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/TimaKeyStoreProvider( 4405): TimaSignature is unavailable
,D/ActivityThread( 4405): Added TimaKeyStore provider
,D/SensorManager( 1017): unregisterListener ::   ,
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb90bd5c8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/Launcher( 1488): onRestart, Launcher: 382595695
,D/Launcher( 1488): onStart, Launcher: 382595695
,D/Launcher.HomeView( 1488): onStart
,D/Launcher( 1488): onResume, Launcher: 382595695
I/GFX raster( 3889): took 0.935105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b518d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b6a990 counterpartCT=4 counterpartW=96 counterparth=96
,D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1488): onResume
,I/AMMetaDataParserService( 3889): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity,
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,I/AMMetaDataParserService( 3889): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.948438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26458 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/MenuAppsGridFragment( 1488): onResume
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0,
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0,
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusChecker( 4405): onReceive : android.intent.action.BOOT_COMPLETED
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/StatusChecker( 4405): onReceive : net.mt.init : DONE
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 1488
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
D/SRIB_DCS( 1488): log_dcs ThreadedRenderer::initialize entered! 
,I/GFX raster( 3889): took 0.859115ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b69390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast,
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3889): took 0.779844ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b79d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,D/Launcher( 1488): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,E/Zygote  ( 4425): MountEmulatedStorage(),
D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/Zygote  ( 4425): v2
I/libpersona( 4425): KNOX_SDCARD checking this for 10116,
I/libpersona( 4425): KNOX_SDCARD not a persona,
,I/SELinux ( 4425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4425 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/SELinux ( 4425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1017): Killing 3594:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
E/SELinux ( 4425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.662291ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,W/IInputConnectionWrapper( 4049): showStatusIcon on inactive InputConnection
I/StatusBar( 1186): Icon Only
D/PanelView( 1186): There is/are notification(s) 
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/SamsungIME( 1845): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3889): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/Timeline( 1488): Timeline: Activity_idle id: android.os.BinderProxy@2a4bf343 time:49032
,W/com.google.a.a.b.d.a( 4297): Application name is not set. Call Builder#setApplicationName.
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.627709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b68038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4425): TimaSignature is unavailable
,D/ActivityThread( 4425): Added TimaKeyStore provider
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.912500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b518d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,I/AMMetaDataParserService( 3889): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3889): getResourceTypeNamexml
I/ActivityManager( 1017): Displayed Component not be shown by security: +342ms
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.799271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26458 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,V/AlarmManager( 1017): waitForAlarm result :8
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3594/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/AndroidRuntime( 4401): 
D/AndroidRuntime( 4401): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.647291ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b69390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b4bc70 counterpartCT=4 counterpartW=96 counterparth=96
,D/AndroidRuntime( 4401): CheckJNI is OFF
,D/AndroidRuntime( 4401): readGMSProperty: start
D/AndroidRuntime( 4401): readGMSProperty: already setted!!
D/AndroidRuntime( 4401): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4401): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4401): readGMSProperty: end
D/AndroidRuntime( 4401): addProductProperty: start
,I/AMMetaDataParserService( 3889): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/PageBuddyNotiSvc( 4425): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/SecKeyguardClockView( 1186): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.701875ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b79d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecKeyguardClockView( 1186): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,I/AMMetaDataParserService( 3889): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/accuweather( 1739): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1739): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1739): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1739): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1739): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1739): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1739): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1739): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1739): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2,
,E/accuweather( 1739): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 16
,W/ContextImpl( 4425): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/SensorService( 1017): [SO] currT = 49240084511, prevT = 48780150605, diff = 459933906, [0.134 0.402 10.151]
,D/SensorService( 1017): [SO] 0.134 0.402 10.151
D/SensorService( 1017): [SO] [100 -> 255]
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4425): onCreate mCpBitFlag=0
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4453 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/GFX raster( 3889): took 0.698646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4453): MountEmulatedStorage()
E/Zygote  ( 4453): v2
I/libpersona( 4453): KNOX_SDCARD checking this for 10125
I/libpersona( 4453): KNOX_SDCARD not a persona
,I/SELinux ( 4453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3889): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/AffinityControl( 4401): AffinityControl: registerfunction enter
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.758646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b68038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bc70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/AndroidRuntime( 4401): Calling main entry com.android.commands.pm.Pm
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4453): TimaSignature is unavailable
D/ActivityThread( 4453): Added TimaKeyStore provider
,D/PackageManager( 1017): START PACKAGE DELETE: observer{300411138}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{2}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10155, uninstall pkg
,W/ResourcesManager( 4453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4453): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4453): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.756823ms for 96*96 texture 0,
I/ActivityManager( 1017): Killing 4049:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b518d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (7/8)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/8)
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{2366cff2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:49485
,W/OpenGLRenderer( 1488): SFEffectCache::get: create texture(0x9f7d4724): name, size, mSize = 39, 145188, 314384
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3889): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/Watchdog( 1017): !@Sync 1
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.689584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26458 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SettingsProvider( 1017): name = audio_safe_volume_state
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.630052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b69390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b4bc70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/CalendarProvider2( 4348): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/QuickConnect( 4453): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4453): Util.setSCRunningSetting - [value]0
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.621042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b79d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b4bd20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.658124ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4bbc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.633281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b68038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bc70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SamsungIME( 1845): mOCRHelper is null
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1856): Ignoring removeGeofence because network location is disabled.
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.724114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b518d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bd20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,I/AMMetaDataParserService( 3889): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.683854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8d26458 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b4bc70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/GFX raster( 3889): took 0.651719ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b69390 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b66e10 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,I/AMMetaDataParserService( 3889): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SettingsProvider( 1017): name = scon_is_running
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10125
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,D/RegisteredComponentCache( 1450): Collect Tech packages for Knox
,I/QuickConnect( 4453): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,D/PersonaManager( 1450): isKioskContainerExistOnDevice
D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,I/SecKeyguardClockSingleView( 1186): Ignore. Because it is same clock text
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.633594ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b79d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b66e10 counterpartCT=4 counterpartW=96 counterparth=96
I/QuickConnect( 4453): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,V/NetworkStats( 1017): removeUidsLocked() for UIDs [10155]
,V/NetworkStats( 1017): performPollLocked(flags=0x3)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,I/AMMetaDataParserService( 3889): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,E/SMD     (  287): DCD OFF,
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10155
,V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3889): took 0.644531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b74f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b66e10 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3889): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4471 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 4471): MountEmulatedStorage()
E/Zygote  ( 4471): v2
I/libpersona( 4471): KNOX_SDCARD checking this for 10131
I/libpersona( 4471): KNOX_SDCARD not a persona
I/SELinux ( 4471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
I/GFX raster( 3889): took 0.676407ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b68038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b66e10 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
V/NetworkStats( 1017): performPollLocked() took 51ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.736615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb8b518d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b66e10 counterpartCT=4 counterpartW=96 counterparth=96
,V/AlarmManagerEXT( 1017): com.test.thalitest(10155) is removed.
,I/AMMetaDataParserService( 3889): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4471): TimaSignature is unavailable
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
D/ActivityThread( 4471): Added TimaKeyStore provider
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/ActivityManager( 1017): Killing 3629:com.sec.esdk.elm/u0a94 (adj 15): empty #31
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.saveres,tore.SaveThreadActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3889): Resource data:Loop for runnin,g activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10155
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/ActivityManager( 1017): Killing 2820:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ResourcesManager( 4471): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4471): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4471): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
D/PersonaManager( 1450): isKioskContainerExistOnDevice
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131165197
D/RegisteredServicesCache( 1450): empty dynamic service
,W/ResourcesManager( 3889): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3889): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,I/AMMetaDataParserService( 3889): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,I/AMMetaDataParserService( 3889): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3889): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/SBrowserFeatureFlag( 4471): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1488): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ManifestProvider( 4471): onCreate()
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131165197
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=12_task.xml
I/AMMetaDataParserService( 3889): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=12_task_thumbnail.png
,I/AMMetaDataParserService( 3889): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/NetworkSettingsReceiver( 4471): onReceive: android.intent.action.BOOT_COMPLETED
,E/SBrowserFeatureFlag( 4471): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@16cdf26f
,D/SBrowserFeatureFlag( 4471): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4471): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/DBG_POLICYDM( 4185): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/AMMetaDataParserService( 3889): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts,
,E/Zygote  ( 4490): MountEmulatedStorage(),
I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4490 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/DBG_POLICYDM( 4185): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/ActivityManager( 1017): Killing 3610:com.wssnps/1000 (adj 15): empty #31
,E/Zygote  ( 4490): v2
I/libpersona( 4490): KNOX_SDCARD checking this for 10135
I/libpersona( 4490): KNOX_SDCARD not a persona,
,I/SELinux ( 4490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3889): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/art     ( 4185): WaitForGcToComplete blocked for 55.241ms for cause HomogeneousSpaceCompact,
,D/TimaKeyStoreProvider( 4490): TimaSignature is unavailable
,D/ActivityThread( 4490): Added TimaKeyStore provider
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  302): Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 31.449ms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 48128(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 30MB/45MB, paused 2.665ms total 554.902ms
,W/ResourcesManager( 4490): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.950ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 18.352ms
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131165197
,I/AMMetaDataParserService( 3889): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,I/AMMetaDataParserService( 3889): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3889): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/daemonapp( 1354): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3889): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3889): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3889): Resource data:Loop for run,ning activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131099648
,I/AMMetaDataParserService( 3889): getResourceName:com.sec.android.app.camera:xml/assistant
W/ResourcesManager( 3889): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
W/ResourcesManager( 3889): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  ( 4510): MountEmulatedStorage(),
E/Zygote  ( 4510): v2
I/libpersona( 4510): KNOX_SDCARD checking this for 10139
I/libpersona( 4510): KNOX_SDCARD not a persona
,I/SELinux ( 4510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4510 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/SELinux ( 4510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4510): TimaSignature is unavailable
,D/ActivityThread( 4510): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3889): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ResourcesManager( 4510): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4510): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4510): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4510): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4510): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4530 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 4530): MountEmulatedStorage(),
,E/Zygote  ( 4530): v2
I/libpersona( 4530): KNOX_SDCARD checking this for 10145
I/libpersona( 4530): KNOX_SDCARD not a persona
,I/SELinux ( 4530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4530): TimaSignature is unavailable
,D/ActivityThread( 4530): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3689:com.sec.factory.camera/1000 (adj 15): empty #31
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4530): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4530): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4530): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4530): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:assistant
I/AMMetaDataParserService( 3889): Resource data:2131165220
,W/ResourcesManager( 3889): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3889): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3889): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3889): getResourceTypeNamexml
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.713333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb927da58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb927d820 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3889): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3889): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3889): took 0.727709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3889): Bitmap=0xb927d900 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9290cc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 3372:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3889): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10155 Target=com.test.thalitest
,D/PackageManager( 1017): result of delete: 1{300411138}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 4401): Shutting down VM
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1017): failed to open /acct/uid_10094/pid_3629/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10120/pid_2820/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3610/cgroup.procs: No such file or directory
,D/PackageManager( 1017): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1017): userId{-1}
D/PackageManager( 1017): andCode{true}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3889): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT,_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
W/ContextImpl( 3889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.AppPicker
I/ActivityManager( 1017): Killing 3732:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.BandMode
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3689/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_3372/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.GSensorSettings
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SViewColor2014
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.sdk.cover.MODE
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity,
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_3732/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
,I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3889): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3889): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
,I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3889): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/dex2oat ( 4218): dex2oat took 5.381s (threads: 4)
,D/DexOptUtils( 2067): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
D/DexOptUtils( 2067): Set odex to world readable.
,D/DexOptUtils( 2067): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/Zygote  ( 4554): MountEmulatedStorage()
E/Zygote  ( 4554): v2
I/libpersona( 4554): KNOX_SDCARD checking this for 10072
I/libpersona( 4554): KNOX_SDCARD not a persona
,I/SELinux ( 4554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4554 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
E/SELinux ( 4554): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3749:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4554): TimaSignature is unavailable
,D/ActivityThread( 4554): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4574): MountEmulatedStorage(),
,E/Zygote  ( 4574): v2
I/libpersona( 4574): KNOX_SDCARD checking this for 10146
I/SELinux ( 4574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/libpersona( 4574): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4574 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/BadgeProvider( 4554): onCreate
D/BadgeProvider( 4554): DatabaseHelper
I/SELinux ( 4574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4574): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Killing 3803:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
I/ActivityManager( 1017): Killing 3783:com.samsung.android.MtpApplication/1000 (adj 15): empty #32
,W/art     ( 4401): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/BadgeProvider( 4554): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 4574): TimaSignature is unavailable
,D/ActivityThread( 4574): Added TimaKeyStore provider
,D/BadgeProvider( 4554): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4554): sendNotify, [notify] : null
D/BadgeProvider( 4554): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4554): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4554): update, [UpdateCount] : 1
,D/Launcher.Model( 1488): reloadBadges entered.
,W/ResourcesManager( 4574): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10022/pid_3749/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3803/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3783/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 4530): Sending signal. PID: 4530 SIG: 9
,I/ActivityManager( 1017): Process com.android.email (pid 4530)(adj 9) has died(179,1068)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/ActivityManager( 1017): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4592): MountEmulatedStorage(),
E/Zygote  ( 4592): v2
I/libpersona( 4592): KNOX_SDCARD checking this for 1000,
I/libpersona( 4592): KNOX_SDCARD not a persona
,I/SELinux ( 4592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4602): MountEmulatedStorage(),
E/Zygote  ( 4602): v2
I/libpersona( 4602): KNOX_SDCARD checking this for 10145
I/libpersona( 4602): KNOX_SDCARD not a persona

```
