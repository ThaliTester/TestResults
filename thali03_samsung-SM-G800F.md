#### Test 539786639813e59_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/ActivityThread( 6646): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
--------- beginning of /dev/log/main
E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6646): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager( 2420): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6646): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
I/SA      ( 5825): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5825): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5825): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5715): loadAuthorityPref(): sEnableAuthority = true
I/Icing.InternalIcingCorporaProvider( 6446): Updating corpora: A: com.test.thalitest, C: MAYBE
W/ContextImpl( 6380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 6676): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6676):  
D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
I/SELinux ( 6676): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6676):  
I/SELinux ( 6676):  
I/SELinux ( 6676): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6676): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6676): >>>>> Normal User
E/dalvikvm( 6676): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6676): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6676): in addTimaSignatureService
D/TimaKeyStoreProvider( 6676): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6676): Added TimaKesytore provider
D/dalvikvm( 6676): GC_CONCURRENT freed 3001K, 31% free 9563K/13680K, paused 3ms+1ms, total 20ms
D/dalvikvm( 6676): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/CapabilityManagerService New( 6676): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 6689): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6689):  
I/ActivityManager( 2420): Killing 5346:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 11% free 9500K/10660K, paused 3ms+3ms, total 33ms
I/SELinux ( 6689): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6689):  
I/SELinux ( 6689):  
I/SELinux ( 6689): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6689): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6689): >>>>> Normal User
E/dalvikvm( 6689): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6689): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9500K/10660K, paused 2ms+3ms, total 25ms
D/TimaKeyStoreProvider( 6689): in addTimaSignatureService
D/TimaKeyStoreProvider( 6689): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6689): Added TimaKesytore provider
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9500K/10660K, paused 2ms+3ms, total 25ms
D/dalvikvm( 6689): GC_CONCURRENT freed 2998K, 31% free 9571K/13684K, paused 3ms+1ms, total 28ms
D/dalvikvm( 6689): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/Icing.InternalIcingCorporaProvider( 6446): UpdateCorporaTask done [took 328 ms] updated apps [took 328 ms] 
I/ActivityManager( 2420): Killing 5780:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
D/PackageIntentReceiver( 6689): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6689): Not GearManger package! 
I/SELinux ( 6702): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6702):  
I/ActivityManager( 2420): Killing 5588:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 6702): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6702):  
I/SELinux ( 6702):  
I/SELinux ( 6702): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6702): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6702): >>>>> Normal User
E/dalvikvm( 6702): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6702): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 6702): in addTimaSignatureService
D/TimaKeyStoreProvider( 6702): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6702): Added TimaKesytore provider
D/dalvikvm( 6702): GC_CONCURRENT freed 3000K, 31% free 9561K/13676K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6702): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/MagazineService Version( 6702): Magazine-Channel: 13
D/MagazineService Version( 6702): Magazine-Provider: 13
D/MagazineService Version( 6702): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 6702): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 6702): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/MagazineService::MagazineService( 6702): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 6715): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6715):  
D/MagazineService::MagazineService( 6702): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/SecureStorage( 1965): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1965): [INFO]: SPID(0x00000006)PID: 6630, TID: 6642
I/ActivityManager( 2420): Killing 6039:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 6715): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6715):  
I/SELinux ( 6715):  
I/SELinux ( 6715): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6715): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6715): >>>>> Normal User
E/dalvikvm( 6715): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 6715): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6715): in addTimaSignatureService
D/TimaKeyStoreProvider( 6715): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6715): Added TimaKesytore provider
,D/dalvikvm( 6715): GC_CONCURRENT freed 3010K, 31% free 9557K/13684K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6715): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/SecureStorage( 6630): [INFO]: SPID(0x00000000)Processing data has been completed
I/SELinux ( 6730): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6730):  
I/SELinux ( 6730): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6730):  
I/SELinux ( 6730):  
I/SELinux ( 6730): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6730): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6730): >>>>> Normal User
E/dalvikvm( 6730): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
E/SELinux ( 6730): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2420): Killing 5795:com.sec.android.soagent/u0a38 (adj 15): empty #43
D/TimaKeyStoreProvider( 6730): in addTimaSignatureService
D/TimaKeyStoreProvider( 6730): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6730): Added TimaKesytore provider
D/dalvikvm( 6730): GC_CONCURRENT freed 2998K, 31% free 9564K/13680K, paused 3ms+2ms, total 20ms
D/dalvikvm( 6730): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/KidsPlatformStub( 6730): Package not found : com.sec.android.app.kidshome
I/SELinux ( 6742): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6742):  
I/ActivityManager( 2420): Killing 6132:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
D/AndroidRuntime( 6727): 
D/AndroidRuntime( 6727): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6727): CheckJNI is OFF
D/AndroidRuntime( 6727): setted country_code = Poland
D/AndroidRuntime( 6727): setted countryiso_code = PL
D/AndroidRuntime( 6727): setted sales_code = PLS
D/AndroidRuntime( 6727): readGMSProperty: start
D/AndroidRuntime( 6727): readGMSProperty: already setted!!
D/AndroidRuntime( 6727): readGMSProperty: end
D/AndroidRuntime( 6727): addProductProperty: start
D/dalvikvm( 6727): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6727): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6727): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6727): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6727): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 6742): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6742):  
I/SELinux ( 6742):  
I/SELinux ( 6742): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6742): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6742): >>>>> Normal User
E/dalvikvm( 6742): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
E/SELinux ( 6742): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6742): in addTimaSignatureService
D/TimaKeyStoreProvider( 6742): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6742): Added TimaKesytore provider
D/dalvikvm( 6742): GC_CONCURRENT freed 3002K, 31% free 9560K/13680K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6742): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/SELinux ( 6761): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6761):  
I/ActivityManager( 2420): Killing 5875:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
I/SELinux ( 6761): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6761):  
I/SELinux ( 6761):  
I/SELinux ( 6761): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6761): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6761): >>>>> Normal User
E/dalvikvm( 6761): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
E/memtrack( 6727): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6727): failed to load memtrack module: -2
E/SELinux ( 6761): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6761): in addTimaSignatureService
D/TimaKeyStoreProvider( 6761): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6761): Added TimaKesytore provider
D/dalvikvm( 6727): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 6761): GC_CONCURRENT freed 2999K, 31% free 9571K/13684K, paused 3ms+1ms, total 19ms
D/dalvikvm( 6761): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/AndroidRuntime( 6727): Calling main entry com.android.commands.am.Am
D/UMC:Core( 6761): onCreate(): 
I/Icing   ( 3570): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/USER_AGENT( 6761): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 6776): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6776):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/AndroidRuntime( 6727): Shutting down VM
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/dalvikvm( 6727): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6776): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6776):  
I/SELinux ( 6776):  
I/SELinux ( 6776): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6776): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6776): >>>>> Normal User
E/dalvikvm( 6776): >>>>> com.test.thalitest [ userId:0 | appId:10561 ]
E/SELinux ( 6776): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6776): in addTimaSignatureService
D/TimaKeyStoreProvider( 6776): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6776): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4172): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4172): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
D/[SAMSUNG SMARCART NATIVE]( 6761): initialize...
D/[SAMSUNG SMARCART NATIVE]( 6761): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/TZ_CCM_C_GetFunctionList: ( 6761): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 6761): FINISHED: initialize rv:0
D/dalvikvm( 6776): GC_CONCURRENT freed 3010K, 31% free 9556K/13680K, paused 2ms+1ms, total 19ms
D/dalvikvm( 6776): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/Icing   ( 3570): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
V/WebViewChromium( 6776): Binding Chromium to the background looper Looper (main, tid 1) {42620270}
I/chromium( 6776): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6776): Initializing chromium process, renderers=0
,W/chromium( 6776): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6776): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6776): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6776): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6776): Mali API Version : 401
,I/Mali    ( 6776): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6776): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6776): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 6776): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6776): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6776): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6776): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2420): tr p:6776,o:f
,W/dalvikvm( 6776): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 6776): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6776): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6776): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 6776): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6776): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6776): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6776): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6776): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 6776): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6776): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6776): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6776): CordovaWebView is running on device made by: samsung
,D/dalvikvm( 6761): GC_CONCURRENT freed 1876K, 22% free 10769K/13756K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 6761): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/StatusBarManagerService( 2420): semi p:6776,o:f
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/UMC:SecurityUtils( 6761): Loaded server certificates: 0
D/UMC:SecurityUtils( 6761): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6761): New Flow
D/TimaService( 2420): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2420): TIMA: in getTimaVersion
I/        ( 2420): CCM JNI: In ccm_register_for_default_cert
I/        ( 2420): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2420): &ctx = 0x7bcfd618
I/TLC_TZ_CCM: ( 2420): creating new ccm context...
I/TLC_TZ_CCM: ( 2420): initializing ccm context...
I/TLC_TZ_CCM: ( 2420): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2420): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2420): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2420): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2420): root = 0, root_len = 1
I/TZ: client_server_communication( 2420): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2420): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2420): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2420): Client_Server_Open was called
I/TZ: client_server_communication( 2420): IClientServer::IClientServer()
I/TZ: client_server_communication( 2420): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2509): creating new ccm context...
I/TZ_CCM_SERVER( 2509): initializing ccm context...
I/TZ_CCM_SERVER( 2509): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2509): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2509): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2509): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2509): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2509): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2509): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2509): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2509): device_id = 0x0
I/TZ: mc_tlc_communication( 2509): tlc_open() was called
I/TZ: mc_tlc_communication( 2509): Opening MobiCore device
I/TZ: mc_tlc_communication( 2509): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2509): Opening the session
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
,I/TZ: mc_tlc_communication( 2509): tlc_open() succeeded
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/TZ: client_server_communication( 2420): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2420): ctx = 0x7bc50958, comm = 0x7bc50790, sendmsg = 0x7bef0008, recvmsg = 0x7bef4c08
I/TZ_init: ( 2420): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
E/Parcel  ( 2509): nm 19456
E/Parcel  ( 2420): nm 19456
E/TZ_init: ( 2420): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2420): trustlet initialization failed
I/TZ_init: ( 2420): TZ_init_START...
I/TZ_init: ( 2420): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
E/Parcel  ( 2509): nm 19456
,E/Parcel  ( 2420): nm 19456
I/TZ_init: ( 2420): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2420): Exercising TZ_DB_INIT in TLC
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
E/Parcel  ( 2509): nm 19456
,I/HWUI    ( 6776): EGLImpl-HWUI Protected EGL context created
E/Parcel  ( 2420): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2420): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: ( 2420): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
E/Parcel  ( 2420): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2420): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2420): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2420): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(2) 16
,E/Parcel  ( 2509): nm 19456
E/Parcel  ( 2420): nm 19456
I/TZ: client_server_communication( 2420): Client_Server_Close was called
I/TZ_CCM_SERVER( 2509): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2509): tlc_close() was called
,I/TZ: mc_tlc_communication( 2509): Closing the session
,D/OpenGLRenderer( 6776): Enabling debug mode 0
I/TZ: mc_tlc_communication( 2509): Free WSM
,I/TZ: mc_tlc_communication( 2509): Closing MobiCore device
W/AwContents( 6776): nativeOnDraw failed; clearing to background color.
I/TZ: mc_tlc_communication( 2509): tlc_close() succeeded
I/TZ: client_server_communication( 2420): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 6761): TIMA service call for password change success!!
D/UMC:AdminManager( 6761): init - start
,D/UMC:AdminManager( 6761): loadAdmins
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/AwContents( 6776): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2420): mDVFSHelper.release()
,W/IInputConnectionWrapper( 6776): showStatusIcon on inactive InputConnection
,D/UMC:AdminManager( 6761): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6761): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6761): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6761): init - end
,V/UMC:AlarmHandler( 6761): Enter loadList
,D/EnterpriseDeviceManagerService( 2420): Creating context as user 0
,D/SPPApp  ( 6761): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6761): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6819): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6819):  
I/ActivityManager( 2420): Killing 6149:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,I/SELinux ( 6819): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6819):  
I/SELinux ( 6819):  
,I/SELinux ( 6819): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6819): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6819): >>>>> Normal User
,E/dalvikvm( 6819): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6819): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6819): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6819): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6819): Added TimaKesytore provider
,D/dalvikvm( 6819): GC_CONCURRENT freed 2989K, 31% free 9574K/13680K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6819): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/ApplicationPromenada( 6819): Application OnCreate start
,D/ApplicationPromenada( 6819): Application OnCreate po on Create
D/CrashReporter( 6819): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@4260d820
D/CrashReporter( 6819): Swaping uncaught exception handler
,D/ApplicationPromenada( 6819): Application OnCreate App Loader start
,D/ApplicationPromenada( 6819): Application OnCreate App Loader finish
,D/p2.ApplicationLoader( 6819): ############################## cached apps: 
,V/WebViewChromium( 6819): Binding Chromium to the background looper Looper (main, tid 1) {426211c0}
,I/chromium( 6819): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6819): Initializing chromium process, renderers=0
,D/JsMessageQueue( 6776): Set native->JS mode to OnlineEventsBridgeMode
,W/chromium( 6819): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6819): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6819): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6819): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6819): Mali API Version : 401
,I/Mali    ( 6819): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6819): Application OnCreate Finish
,D/dalvikvm( 6776): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426180f0
I/ActivityManager( 2420): Killing 6161:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/dalvikvm( 6776): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426180f0
D/jxcore_app_log( 6776): JniHelper::setJavaVM(0x41baf220), pthread_self() = 2030931024
,D/JX-Cordova( 6776): jxcore cordova android initializing
,D/PackageBroadcastService( 3570): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3570): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3570): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3570): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3570): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3570): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3570): Submit a task: k
,D/ChimeraCfgMgr( 3570): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 3570): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 3570): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 3570): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3570): Found info for package com.test.thalitest in db.
,D/dalvikvm( 6776): GC_CONCURRENT freed 1289K, 18% free 11340K/13740K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 6776): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 6776): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/Finsky  ( 3826): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 6819): GC_CONCURRENT freed 1784K, 22% free 10810K/13708K, paused 12ms+3ms, total 69ms
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6776): GC_CONCURRENT freed 1952K, 18% free 14900K/17976K, paused 3ms+3ms, total 58ms
,D/dalvikvm( 6776): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 6819): GC_CONCURRENT freed 2362K, 25% free 10431K/13904K, paused 3ms+3ms, total 40ms
,W/ResourceType( 6819): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6819): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6819): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6819): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6819): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6819): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6819): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6819): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6819): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6819): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6819): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6819): 	at java.lang.Thread.run(Thread.java:841)
,I/Icing   ( 3570): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/PowerManagerService( 2420): [PWL] Off : 75s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3570, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=1194)
,D/dalvikvm( 6776): GC_FOR_ALLOC freed 5393K, 30% free 16240K/22944K, paused 45ms, total 54ms
,I/Icing   ( 3570): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 6819): GC_CONCURRENT freed 2045K, 26% free 10324K/13904K, paused 2ms+4ms, total 30ms
,D/dalvikvm( 6776): GC_CONCURRENT freed 6727K, 31% free 17679K/25544K, paused 1ms+10ms, total 66ms
,D/dalvikvm( 6776): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 6776): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/p2.ApplicationLoader( 6819): Process time: 2678
,D/p2.ApplicationLoader( 6819): ##############################  apps after loading: 
,D/dalvikvm( 6819): GC_CONCURRENT freed 1907K, 26% free 10366K/13904K, paused 2ms+3ms, total 45ms
,D/dalvikvm( 6776): GC_FOR_ALLOC freed 1579K, 32% free 17385K/25544K, paused 38ms, total 39ms
,I/dalvikvm-heap( 6776): Grow heap (frag case) to 21.654MB for 3767174-byte allocation
,D/dalvikvm( 6776): GC_FOR_ALLOC freed 2507K, 37% free 18557K/29224K, paused 34ms, total 34ms
,W/jxcore-log( 6776): Initializing JXcore engine
,W/jxcore-log( 6776): JXcore engine is ready
,W/jxcore-log( 6776): Starting JXcore engine
,W/jxcore-log( 6776): Platform android
W/jxcore-log( 6776): 
,W/jxcore-log( 6776): Process ARCH arm
W/jxcore-log( 6776): 
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5892): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5892): Breath 71951 latestRequest time : 1450361467901 current time : 1450361539852
,I/VacuumService( 2734): Vacuum at: now=1450361540082 tag=VacuumService
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 6776): JXcore Cordova bridge is ready!
I/jxcore-log( 6776): 
,W/jxcore-log( 6776): JXcore engine is started
,I/chromium( 6776): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6776): Toggling radios to true
I/jxcore-log( 6776): 
,D/BluetoothAdapter( 6776): enable(): BT is already enabled..!
,I/WifiManager( 6776): packageName : com.test.thalitest
I/WifiManager( 6776): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=6776, uid=10561
W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=6776, uid=10561 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6776, uid=10561 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2420): disconnect: pid=6776, uid=10561
,I/jxcore-log( 6776): Radios toggled
I/jxcore-log( 6776): 
,I/wpa_supplicant( 3975): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3975): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3975): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3975): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3975): First Scan Start
,W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3975): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/CommandListener( 1917): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3975): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3975): Skip scan - already scanning
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 6871): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6871):  
D/ConnectivityService( 2420): Attempting to switch to mobile
D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1917): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1917): RTNETLINK answers: No such process
,V/RouteController( 1917): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1917): RTNETLINK answers: No such file or directory
,D/CommandListener( 1917): Clearing all IP addresses on wlan0
I/SELinux ( 6871): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6871):  
I/SELinux ( 6871):  
,I/SELinux ( 6871): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6871): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6871): >>>>> Normal User
,E/dalvikvm( 6871): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,W/NetworkManagementService( 2420): route cmd failed: 
W/NetworkManagementService( 2420): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2420): '
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2420): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2420): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,E/SELinux ( 6871): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1917): /system/bin/ip -4 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1917): RTNETLINK answers: No such process
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-78ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1917): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-79ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1917): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x750d10a0 clazz=0x61700001 iface=wlan0 mask=0x3
,D/TimaKeyStoreProvider( 6871): in addTimaSignatureService
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 6871): Cannot add TimaSignature Service, License check Failed
,E/SPPClientService( 5562): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,D/ActivityThread( 6871): Added TimaKesytore provider
,E/SPPClientService( 5562): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5562): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5562): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5562): [b] ResponseMap empty
,V/NativeCrypto( 2848): Read error: ssl=0x7a2398e0: I/O error during system call, Connection timed out
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7a2398e0: I/O error during system call, Broken pipe
,V/NetworkStats( 2420): updateIfacesLocked()
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2420): performPollLocked() took 32ms
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/dalvikvm( 6871): GC_CONCURRENT freed 2993K, 31% free 9571K/13676K, paused 17ms+1ms, total 48ms
,D/dalvikvm( 6871): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 6871): Inside WakeupProvider
,I/System.out( 6871): Inside onCreate() of WakeupTriggerProvide
,D/dalvikvm( 2420): GC_EXPLICIT freed 25259K, 74% free 25577K/95356K, paused 14ms+23ms, total 334ms
,I/VlingoApplication( 6871): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6871): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6871): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2420): Killing 5333:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
D/DialogFlow( 6871): initQueue()
D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2420): updateDataUsageMap
D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6600): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6600): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6600): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6600): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6600): noConnectivity : true
,I/SELinux ( 6900): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6900):  
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 6900): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6900):  
I/SELinux ( 6900):  
,I/SELinux ( 6900): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6900): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6900): >>>>> Normal User
,E/dalvikvm( 6900): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6900): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6900): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6900): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6900): Added TimaKesytore provider
,D/dalvikvm( 6900): GC_CONCURRENT freed 2997K, 31% free 9565K/13680K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6900): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/ActivityManager( 2420): Killing 6189:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,I/wpa_supplicant( 3975): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 3975): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3975): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/SELinux ( 6914): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6914):  
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3975): Associated with C0.AA.48
I/wpa_supplicant( 3975): freq(2412) increment count 2
,I/wpa_supplicant( 3975): meet head of list.
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/SELinux ( 6914): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6914):  
I/SELinux ( 6914):  
,I/SELinux ( 6914): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6914): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6914): >>>>> Normal User
,E/dalvikvm( 6914): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 6914): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6914): in addTimaSignatureService
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3975): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3975): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3975): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/TimaKeyStoreProvider( 6914): Cannot add TimaSignature Service, License check Failed
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/ActivityThread( 6914): Added TimaKesytore provider
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 6914): GC_CONCURRENT freed 3000K, 31% free 9563K/13676K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 6914): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/ActivityManager( 2420): Killing 6262:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/SELinux ( 6926): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6926):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 11% free 9500K/10660K, paused 4ms+3ms, total 29ms
,I/SELinux ( 6926): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6926):  
I/SELinux ( 6926):  
,I/SELinux ( 6926): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6926): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6926): >>>>> Normal User
,E/dalvikvm( 6926): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6926): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9500K/10660K, paused 2ms+3ms, total 23ms
,D/TimaKeyStoreProvider( 6926): in addTimaSignatureService
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9500K/10660K, paused 2ms+2ms, total 23ms
,D/TimaKeyStoreProvider( 6926): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6926): Added TimaKesytore provider
,D/dalvikvm( 6926): GC_CONCURRENT freed 2997K, 31% free 9570K/13684K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6926): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/dhcpcd  ( 6938): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6938): bssid match
,D/KLMS-2.3.201 : ( 6926): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 6926): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361542656
,I/KLMS-2.3.201 : ( 6926): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2420): Killing 6321:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 6945): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6945):  
,I/SELinux ( 6945): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6945):  
I/SELinux ( 6945):  
,I/SELinux ( 6945): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6945): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6945): >>>>> Normal User
,E/dalvikvm( 6945): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 6945): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6945): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6945): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6945): Added TimaKesytore provider
,D/dalvikvm( 6945): GC_CONCURRENT freed 3007K, 31% free 9563K/13684K, paused 4ms+1ms, total 23ms
,D/dalvikvm( 6945): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/SO_AGENT( 6945): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 6945): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5825): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5825): [BDLM] already registered in spp
I/SA      ( 5825): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5825): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5825): [OR] == isSIMCardReady false ==
I/SA      ( 5825): [SCU] == networkStateCheck == false
,I/SA      ( 5825): [OR] onReceive END
I/ActivityManager( 2420): Killing 6362:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 6977): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6977):  
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 6977): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6977):  
I/SELinux ( 6977):  
,I/SELinux ( 6977): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6977): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6977): >>>>> Normal User
,E/dalvikvm( 6977): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,D/WifiStateMachine( 2420): VerifyingLinkState enter
,E/SELinux ( 6977): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/TimaKeyStoreProvider( 6977): in addTimaSignatureService
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/TimaKeyStoreProvider( 6977): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6977): Added TimaKesytore provider
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1917): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 370, Delta = 20
,V/RouteController( 1917): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1917): RTNETLINK answers: No such file or directory
,V/RouteController( 1917): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1917): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1917): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1917): RTNETLINK answers: No such process
,V/RouteController( 1917): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1917): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2420): updateIfacesLocked()
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked() took 21ms
D/dalvikvm( 6977): GC_CONCURRENT freed 2994K, 31% free 9568K/13680K, paused 3ms+16ms, total 97ms
D/dalvikvm( 6977): WAIT_FOR_CONCURRENT_GC blocked 87ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/sCloudBackupApp( 6977): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6977): Other Intent
I/ActivityManager( 2420): Killing 6406:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7006): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7006):  
,I/SELinux ( 7006): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7006):  
I/SELinux ( 7006):  
,I/SELinux ( 7006): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7006): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7006): >>>>> Normal User
,E/dalvikvm( 7006): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7006): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7006): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7006): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7006): Added TimaKesytore provider
,D/dalvikvm( 7006): GC_CONCURRENT freed 2998K, 31% free 9568K/13680K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7006): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7006): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7006): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5359): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7006): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5359): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7006): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5359): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 5608:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5892): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5892): getCountryCode(): countryCode = PL
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5892): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5892): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5892): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5892): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5892): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5892): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7018): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7018):  
,I/SELinux ( 7018): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7018):  
I/SELinux ( 7018):  
,I/SELinux ( 7018): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7018): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7018): >>>>> Normal User
,E/dalvikvm( 7018): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7018): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7018): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7018): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7018): Added TimaKesytore provider
,D/dalvikvm( 7018): GC_CONCURRENT freed 2994K, 31% free 9569K/13680K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7018): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,V/WebViewChromium( 7018): Binding Chromium to the background looper Looper (main, tid 1) {4261e0e0}
,I/chromium( 7018): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7018): Initializing chromium process, renderers=0
,D/libEGL  ( 7018): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7018): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7018): loaded /system/lib/egl/libGLESv2_mali.so
,W/chromium( 7018): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Mali    ( 7018): Mali API Version : 401
,I/Mali    ( 7018): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1913): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7018): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Vold    ( 1913): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7018): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/NSApplication( 7018): Starting up...
,I/iu.Environment( 5956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
I/ActivityManager( 2420): Killing 4879:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5159): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5159): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5159): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4262c968
,I/SELinux ( 7056): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7056):  
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7056): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7056):  
I/SELinux ( 7056):  
,I/SELinux ( 7056): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7056): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7056): >>>>> Normal User
,E/dalvikvm( 7056): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7056): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7056): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7056): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7056): Added TimaKesytore provider
,D/dalvikvm( 7056): GC_CONCURRENT freed 2988K, 30% free 9583K/13684K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7056): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7075): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7075):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7075): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7075):  
I/SELinux ( 7075):  
,I/SELinux ( 7075): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7075): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7075): >>>>> Normal User
,E/dalvikvm( 7075): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7075): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2420): Killing 6460:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7075): in addTimaSignatureService
W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 7075): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7075): Added TimaKesytore provider
,I/SELinux ( 7087): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7087):  
,I/ActivityManager( 2420): Killing 6327:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7087): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7087):  
I/SELinux ( 7087):  
,I/SELinux ( 7087): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7087): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7087): >>>>> Normal User
,E/dalvikvm( 7087): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7087): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7087): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7087): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7087): Added TimaKesytore provider
,D/dalvikvm( 7075): GC_CONCURRENT freed 3002K, 31% free 9563K/13680K, paused 19ms+1ms, total 49ms
,D/dalvikvm( 7075): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/BadgeProvider( 7075): onCreate
,D/BadgeProvider( 7075): DatabaseHelper
,D/BadgeProvider( 7075): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7087): GC_CONCURRENT freed 3006K, 31% free 9563K/13684K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7087): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/BadgeProvider( 7075): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7075): sendNotify, [notify] : null
D/BadgeProvider( 7075): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7075): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7075): update, [UpdateCount] : 1
,D/Launcher.Model( 2770): reloadBadges entered.
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,E/SPPClientService( 5562): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [SystemStateMoniter] Current Time : 150911
,E/SPPClientService( 5562): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5562): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5562): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5562): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6600): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6600): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6600): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6600): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SPPClientService( 5562): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 6926): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 6926): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361545408
,I/KLMS-2.3.201 : ( 6926): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 3375): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/SO_AGENT( 6945): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/GalaxyFinderApplication( 3375): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3375): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 6945): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3375): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3518): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7110): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7110):  
,I/SELinux ( 7110): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7110):  
I/SELinux ( 7110):  
,I/SELinux ( 7110): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7110): >>>>> Normal User
,E/dalvikvm( 7110): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7121): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7121):  
D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      ( 5825): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5825): [BDLM] already registered in spp
,I/SA      ( 5825): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5825): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SELinux ( 7121): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7121):  
I/SELinux ( 7121):  
,I/SELinux ( 7121): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7121): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7110): in addTimaSignatureService
E/dalvikvm( 7121): >>>>> Normal User
,E/dalvikvm( 7121): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
I/SA      ( 5825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5825): [OR] == isSIMCardReady false ==
,I/SA      ( 5825): [SCU] == networkStateCheck == true
E/SELinux ( 7121): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5825): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5825): isChinaCountryCode : false
,I/SA      ( 5825): [OR] == networkStateCheck true ==
,I/SA      ( 5825): [OR] GetMyCountryZoneTask
,D/TimaKeyStoreProvider( 7110): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7110): Added TimaKesytore provider
,I/SA      ( 5825): [OR] onReceive END
,I/SA      ( 5825): [SRS] prepareGetMyCountryZone
,I/SA      ( 5825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5825): [SSP] query invoked
,D/TimaKeyStoreProvider( 7121): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7121): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7121): Added TimaKesytore provider
,I/SA      ( 5825): [TPMU] GetMccFromDB : null
,I/SA      ( 5825): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5825): [TPM] isNoProxy(default) : true
,I/SA      ( 5825): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6977): Other Intent
D/dalvikvm( 7110): GC_CONCURRENT freed 2992K, 31% free 9571K/13676K, paused 5ms+1ms, total 38ms
,D/dalvikvm( 7110): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 7121): GC_CONCURRENT freed 3002K, 31% free 9564K/13684K, paused 13ms+1ms, total 42ms
,D/dalvikvm( 7121): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/jxcore-log( 6776): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 6776): 
,I/jxcore-log( 6776): my name is : samsung-SM-G800F_PT6138
I/jxcore-log( 6776): 
,V/KVNProvider( 7121): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7121): getFindoCursor query string : 
,V/KVNProvider( 7121): getTagSearchCursor() tagSearchCursor count : 0
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7006): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 6342:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/dalvikvm( 6914): Total arena pages for JIT: 11
,I/dalvikvm( 6914): Total arena pages for JIT: 12
I/dalvikvm( 6914): Total arena pages for JIT: 13
I/dalvikvm( 6914): Total arena pages for JIT: 14
I/dalvikvm( 6914): Total arena pages for JIT: 15
I/dalvikvm( 6914): Total arena pages for JIT: 16
,I/dalvikvm( 6914): Total arena pages for JIT: 17
,D/Headlines( 5892): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5892): getCountryCode(): countryCode = PL
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5892): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5892): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5892): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5892): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5892): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5892): requestUpdateNewsWelcomeCard !!! no welcome card
,I/jxcore-log( 6776): attempting to connect to test coordinator
I/jxcore-log( 6776): 
,I/jxcore-log( 6776): check test folder
I/jxcore-log( 6776): 
,I/jxcore-log( 6776): found test : ./testFindPeers.js
I/jxcore-log( 6776): 
,I/iu.Environment( 5956): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5159): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5159): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5159): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4262c968
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/jxcore-log( 6776): found test : ./testReConnect.js
I/jxcore-log( 6776): 
,I/jxcore-log( 6776): found test : ./testSendData.js
I/jxcore-log( 6776): 
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,D/PackageManager( 2420): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@447f92f8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/System.out( 6914): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,I/jxcore-log( 6776): Test app app.js loaded
I/jxcore-log( 6776): 
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/SPPClientService( 5562): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [SystemStateMoniter] Current Time : 152195
,I/System.out( 6914): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 6914): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 6776): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6776): 
,D/RegisteredServicesCache( 2756): empty dynamic service
,I/chromium( 6776): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SPPClientService( 5562): [SystemStateMoniter] No Connect : false
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/Icing.InternalIcingCorporaProvider( 6446): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,I/SELinux ( 7144): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7144):  
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD,
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,I/SELinux ( 7144): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7144):  
I/SELinux ( 7144):  
,I/SELinux ( 7144): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7144): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7144): >>>>> Normal User
,E/dalvikvm( 7144): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ],
,E/SELinux ( 7144): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/System.out( 6914): AsyncTask #1 calls detatch(),
,D/TimaKeyStoreProvider( 7144): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7144): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7144): Added TimaKesytore provider,
,D/dalvikvm( 5562): GC_CONCURRENT freed 1978K, 24% free 10436K/13660K, paused 10ms+5ms, total 81ms,
,I/Icing.InternalIcingCorporaProvider( 6446): UpdateCorporaTask done [took 228 ms] updated apps [took 227 ms] ,
,W/System.err( 6914): com.sec.android.fota.osp.http.RestClientException,
W/System.err( 6914): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6914): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6914): 	,at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6914): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 6914): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6914): 	,at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6914): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6914): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6914): 	,at java.lang.Thread.run(Thread.java:841)
W/System.err( 6914): Caused by: java.lang.NullPointerException
W/System.err( 6914): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 6914): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157),
W/System.err( 6914): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6914): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6914): ,	... 8 more
,I/ActivityManager( 2420): Killing 5998:com.android.calendar/u0a144 (adj 15): empty #43,
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/dalvikvm( 2420): GC_EXPLICIT freed 3022K, 74% free 25689K/95356K, paused 15ms+20ms, total 230ms,
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/HarmonyEASService( 2420): Updating for all 1,
D/dalvikvm( 7144): GC_CONCURRENT freed 3001K, 31% free 9564K/13680K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7144): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,D/FileShare-Server( 7144): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/SELinux ( 7158): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7158):  
I/ActivityManager( 2420): Killing 6283:com.android.providers.calendar/u0a45 (adj 15): empty #43
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 11% free 9500K/10660K, paused 3ms+4ms, total 41ms
I/SELinux ( 7158): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7158):  
I/SELinux ( 7158):  
,I/SELinux ( 7158): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7158): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7158): >>>>> Normal User
,E/dalvikvm( 7158): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 7158): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 5825): [RC New] [v2liruge] api execute + 1392
I/SA      ( 5825): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9500K/10660K, paused 2ms+4ms, total 31ms
,I/System.out( 5825): AsyncTask #2 calls detatch()
,D/TimaKeyStoreProvider( 7158): in addTimaSignatureService
,I/SA      ( 5825): [TPMU] getNetworkMcc : 
,D/TimaKeyStoreProvider( 7158): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7158): Added TimaKesytore provider
,I/SA      ( 5825): [SCU] saveMccToPreferece Start
,I/SA      ( 5825): [SCU] RegionMCC : 260
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 11% free 9500K/10660K, paused 2ms+4ms, total 32ms
,I/SA      ( 5825): [SSP] query invoked
,I/SA      ( 5825): [TPMU] GetMccFromDB : null
,I/SA      ( 5825): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5825): [SCU] saveMccToPreferece End
I/SA      ( 5825): [RC New] executeRequest [v2liruge] end. 1457
,I/SA      ( 5825): [RC New] Execute end
,I/SA      ( 5825): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5825): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 6776): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6776): 
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/dalvikvm( 7158): GC_CONCURRENT freed 3010K, 31% free 9557K/13684K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7158): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ApplicationsProvider( 2961): Could not fetch usage stats
W/ApplicationsProvider( 2961): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2961): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2961): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2961): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2961): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2961): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/BezelQuickConnect( 5171): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5171): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,D/PackageBroadcastService( 3570): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/ActivityManager( 2420): Killing 6176:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
E/SPPClientService( 5562): [b] __InitReply__
D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
I/Icing   ( 3570): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
I/Icing   ( 3570): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/ActivityManager( 2420): Killing 6211:com.google.android.music:main/u0a125 (adj 15): empty #43
I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 154638
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3486)
,I/GAV2    ( 7018): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6776): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6776): 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6600): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6600): [hasSamungAccount] - No Samsung Account
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 7186
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6600): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6600): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6600): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6600): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6600): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6600): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6600): [ensureRegistration] - No Samsung account
,I/dalvikvm( 6776): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6776): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6776): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 6776): Shutting down VM
,W/dalvikvm( 6776): threadid=1: thread exiting with uncaught exception (group=0x41bc2c08)
,E/AndroidRuntime( 6776): FATAL EXCEPTION: main
E/AndroidRuntime( 6776): Process: com.test.thalitest, PID: 6776
E/AndroidRuntime( 6776): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6776): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 6776): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 6776): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 6776): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 6776): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:153)
E/AndroidRuntime( 6776): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 6776): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6776): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6776): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6776): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6776): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6776): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6776): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6776): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6776): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6776): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2420):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2420): Killing 6545:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/CrashAnrDetector( 2420): processName: com.test.thalitest
,I/Process ( 6776): Sending signal. PID: 6776 SIG: 9
,D/CrashAnrDetector( 2420): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.acquire()
,I/DBG_DM  ( 4758): [3.19.140541][Line:408][onResume] 
,I/ActivityManager( 2420): Process com.test.thalitest (pid 6776) (adj 9) has died.
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
,I/WindowState( 2420): WIN DEATH: Window{46553e08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DBG_DM  ( 4758): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4758): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4758): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4758): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
,I/DBG_DM  ( 4758): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4758): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4758): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4758): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4758): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4758): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4758): setTransGradationMode to true
,D/PhoneStatusBar( 2578): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4758): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2420): semi p:4758,o:t
,I/SurfaceFlinger( 1922): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 6776 uid 10561
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 3826): GC_CONCURRENT freed 7984K, 36% free 16329K/25424K, paused 8ms+4ms, total 87ms
,D/dalvikvm( 3826): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/Finsky  ( 3826): [214] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3826): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 360, Delta = -10,
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
,D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5892): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5892): Breath 11962 latestRequest time : 1450361545975 current time : 1450361557938
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{43461ce8 u0 com.sec.spp.push/.PushClientService},
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2420): !@Sync 5,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 340, Delta = -20,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 105s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 6,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2420): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5892): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5892): Breath 58986 latestRequest time : 1450361545975 current time : 1450361604961
,I/SELinux ( 7407): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7407):  
,I/SELinux ( 7407): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7407):  
I/SELinux ( 7407):  
,I/SELinux ( 7407): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7407): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,E/dalvikvm( 7407): >>>>> Normal User
,E/dalvikvm( 7407): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 7407): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7407): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7407): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7407): Added TimaKesytore provider
,D/dalvikvm( 7407): GC_CONCURRENT freed 3014K, 31% free 9557K/13684K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7407): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/SPPClientService( 7407): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7407): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7407): PushLog.txt file is not deleted.
,D/SPPClientService( 7407): PushLog.txt file is not deleted.
,D/SPPClientService( 7407): ============PushLog. stop!
,E/SPPClientService( 5562): [b] __PingReply__
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/BatteryService( 2420): stay LED for fully charged
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4005): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5892): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5892): Breath 71952 latestRequest time : 1450361545975 current time : 1450361617927,
,E/Watchdog( 2420): !@Sync 7,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5892): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5892): Breath 101952 latestRequest time : 1450361545975 current time : 1450361647927,
,E/Watchdog( 2420): !@Sync 8,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4005): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5892): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5892): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5892): Breath 131956 latestRequest time : 1450361545975 current time : 1450361677931,
,D/Headlines( 5892): stop ,
,D/Headlines( 5892): Breath.onDestroy : ,
I/ActivityManager( 2420): Killing 6466:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/Watchdog( 2420): !@Sync 9,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2420): initializing...,
I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2420): device_id = 0x0
I/TZ: mc_tlc_communication( 2420): tlc_open() was called
,I/TZ: mc_tlc_communication( 2420): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2420): Opening the session
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 10,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2420): [PWL] Off : 275s ago,
,E/Watchdog( 2420): !@Sync 11,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7763): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7763):  
,I/SELinux ( 7763): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7763):  
I/SELinux ( 7763):  
,I/SELinux ( 7763): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7763): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7763): >>>>> Normal User
,E/dalvikvm( 7763): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7763): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7763): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7763): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7763): Added TimaKesytore provider
,D/dalvikvm( 7763): GC_CONCURRENT freed 3001K, 31% free 9567K/13684K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7763): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/ActivityManager( 2420): Killing 6575:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,E/Watchdog( 2420): !@Sync 12,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 330s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2420): !@Sync 13,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2420): GC_CONCURRENT freed 4347K, 74% free 25289K/95356K, paused 11ms+21ms, total 223ms,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4005): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4005): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2420): !@Sync 14,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 15
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 16
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,E/Watchdog( 2420): !@Sync 17
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2578): GC_CONCURRENT freed 15737K, 34% free 33857K/50704K, paused 15ms+8ms, total 158ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 18
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 19
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 20
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 21
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :8
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2420): LightSensor setDelay = 200000000
,D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
,D/Sensors ( 2420): LightSensor enableSensor = 1
I/PowerManagerService( 2420): [PWL] Off : 600s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=4)
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 5
D/Sensors ( 2420): LightSensor enable = 0
D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 5649): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5649): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2420): !@Sync 22
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 23
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 24
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 25
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4083): GC_CONCURRENT freed 2894K, 30% free 9723K/13732K, paused 19ms+2ms, total 87ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 26
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 27
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 28
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 4093K, 74% free 25085K/95284K, paused 28ms+18ms, total 258ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 29
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 30
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 32
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 34
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,E/SPPClientService( 5562): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2770): GC_CONCURRENT freed 7050K, 39% free 18939K/30600K, paused 17ms+7ms, total 109ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 39
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 40
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 41
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :8
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2420): LightSensor setDelay = 200000000
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
,D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3785K, 74% free 25096K/95284K, paused 22ms+18ms, total 241ms
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,E/Watchdog( 2420): !@Sync 44
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 46
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 48
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 49
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4083): GC_CONCURRENT freed 2050K, 30% free 9721K/13732K, paused 13ms+6ms, total 53ms
,D/dalvikvm( 4083): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 50
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 10565
,D/dalvikvm( 3570): GC_CONCURRENT freed 2152K, 21% free 12606K/15872K, paused 15ms+10ms, total 131ms
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x003d
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 51
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 52
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 54
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 3893K, 74% free 25079K/95284K, paused 17ms+19ms, total 223ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,E/Watchdog( 2420): !@Sync 56
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 58
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 11164
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 60
,I/PowerManagerService( 2420): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 61
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 43ms
,I/ProcessStatsService( 2420): Prepared write state in 65ms
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-31-20.bin
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 62
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2420): stay LED for fully charged
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 64
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2420): [PWL] Off : 1890s ago
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
D/AndroidRuntime(11579): 
D/AndroidRuntime(11579): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11579): CheckJNI is OFF
D/AndroidRuntime(11579): setted country_code = Poland
D/AndroidRuntime(11579): setted countryiso_code = PL
D/AndroidRuntime(11579): setted sales_code = PLS
D/AndroidRuntime(11579): readGMSProperty: start
D/AndroidRuntime(11579): readGMSProperty: already setted!!
D/AndroidRuntime(11579): readGMSProperty: end
D/AndroidRuntime(11579): addProductProperty: start
D/dalvikvm(11579): Trying to load lib libjavacore.so 0x0
D/dalvikvm(11579): Added shared lib libjavacore.so 0x0
D/dalvikvm(11579): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(11579): Added shared lib libnativehelper.so 0x0
D/dalvikvm(11579): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(11579): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(11579): failed to load memtrack module: -2
D/dalvikvm(11579): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(11579): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2420): START PACKAGE DELETE: observer{1126408696}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2420): !@killApplicatoin: 10561, uninstall pkg
I/ActivityManager( 2420): Killing 7121:com.sec.android.app.voicenote/1000 (adj 15): empty for 1815s
I/ActivityManager( 2420): Killing 7110:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1815s
I/ActivityManager( 2420): Killing 5825:com.osp.app.signin/u0a44 (adj 15): empty for 1815s
I/ActivityManager( 2420): Killing 6630:com.policydm/1000 (adj 15): empty for 1815s
I/ActivityManager( 2420): Killing 6945:com.sec.android.soagent/u0a38 (adj 15): empty for 1815s
I/ActivityManager( 2420): Killing 6871:com.vlingo.midas/u0a34 (adj 15): empty for 1815s
I/ActivityManager( 2420): Killing 6926:com.samsung.klmsagent/u0a18 (adj 15): empty for 1816s
I/ActivityManager( 2420): Killing 6914:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1816s
I/ActivityManager( 2420): Killing 5767:com.sec.android.diagmonagent/1000 (adj 15): empty for 1816s
I/ActivityManager( 2420): Killing 6900:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1816s
I/ActivityManager( 2420): Killing 6600:com.sec.pcw.device/1000 (adj 15): empty for 1816s
I/ActivityManager( 2420): Killing 7075:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1816s
I/ActivityManager( 2420): Killing 6423:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1824s
I/ActivityManager( 2420): Killing 6819:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1825s
I/ActivityManager( 2420): Killing 6761:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1826s
I/ActivityManager( 2420): Killing 6742:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1826s
I/ActivityManager( 2420): Killing 6730:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1826s
I/ActivityManager( 2420): Killing 6715:com.samsung.helphub/1000 (adj 15): empty for 1826s
I/ActivityManager( 2420): Killing 6702:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1826s
I/ActivityManager( 2420): Killing 6689:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1827s
I/ActivityManager( 2420): Killing 6676:com.sec.android.service.cm/u0a82 (adj 15): empty for 1827s
I/ActivityManager( 2420): Killing 6380:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1827s
I/ActivityManager( 2420): Killing 5715:com.android.mms/u0a49 (adj 15): empty for 1827s
I/ActivityManager( 2420): Killing 6646:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1827s
I/ActivityManager( 2420): Killing 6020:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1827s
I/ActivityManager( 2420): Killing 6614:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1828s
I/ActivityManager( 2420): Killing 6588:com.android.musicfx/u0a24 (adj 15): empty for 1828s
D/CountryDetector( 2420): No listener is left
W/PackageSettings( 2420): Skipping PackageSetting{42c84c08 com.example.hello/10551} due to missing metadata
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10561, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6446): GC_EXPLICIT freed 2512K, 28% free 9883K/13680K, paused 4ms+6ms, total 73ms
D/dalvikvm( 3570): GC_EXPLICIT freed 233K, 23% free 12374K/15868K, paused 8ms+10ms, total 93ms
E/SamsungIME( 3003): mOCRHelper is null
D/dalvikvm( 2961): GC_EXPLICIT freed 1476K, 27% free 10033K/13684K, paused 10ms+11ms, total 119ms
I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 5159): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10561, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (11609): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11609):  
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/SELinux (11609): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11609):  
I/SELinux (11609):  
I/SELinux (11609): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11609): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11609): >>>>> Normal User
E/dalvikvm(11609): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (11609): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(11609): in addTimaSignatureService
D/TimaKeyStoreProvider(11609): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11609): Added TimaKesytore provider
D/RegisteredServicesCache( 2756): empty dynamic service
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2420): GC_EXPLICIT freed 3996K, 74% free 25006K/95284K, paused 19ms+19ms, total 332ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 42ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 43ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 43ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 44ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 117ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2420): PackageReceiver onReceive()
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2420): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
D/dalvikvm(11609): GC_CONCURRENT freed 2998K, 31% free 9563K/13680K, paused 11ms+2ms, total 55ms
D/dalvikvm(11609): WAIT_FOR_CONCURRENT_GC blocked 43ms
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(11609): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(11609): ELMEngine.ELMEngine( context ).
D/elm:14132(11609): MDMBridge.setEnterpriseBridge()
D/elm:14132(11609): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(11609): ElmAgentService : onCreate()
D/elm:14132(11609): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(11609): MainReceiver.listeningToPackageRemoved()
D/elm:14132(11609): MDMBridge.getInstance()
D/elm:14132(11609): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (11622): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11622):  
D/dalvikvm( 2756): GC_CONCURRENT freed 1209K, 28% free 10612K/14576K, paused 10ms+3ms, total 93ms
D/dalvikvm( 2756): WAIT_FOR_CONCURRENT_GC blocked 74ms
D/elm:14132(11609): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
D/elm:14132(11609): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux (11622): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11622):  
I/SELinux (11622):  
I/SELinux (11622): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11622): >>>>> Normal User
E/dalvikvm(11622): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
D/elm:14132(11609): ElmAgentService : onDestroy().
E/SELinux (11622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2420): Killing 6977:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1816s
D/TimaKeyStoreProvider(11622): in addTimaSignatureService
D/TimaKeyStoreProvider(11622): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11622): Added TimaKesytore provider
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(11622): GC_CONCURRENT freed 3002K, 31% free 9566K/13684K, paused 3ms+2ms, total 36ms
D/dalvikvm(11622): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 2420): GC_EXPLICIT freed 904K, 74% free 24997K/95284K, paused 10ms+31ms, total 410ms
E/Watchdog( 2420): !@Sync 65
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2420): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2420): removePackageParticipantsLocked: uid=10561 #1
I/SELinux (11637): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11637):  
I/ActivityManager( 2420): Killing 7006:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1816s
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (11637): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11637):  
I/SELinux (11637):  
I/SELinux (11637): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11637): >>>>> Normal User
E/dalvikvm(11637): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (11637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager( 2420): delete sourFile : 
D/TimaKeyStoreProvider(11637): in addTimaSignatureService
D/TimaKeyStoreProvider(11637): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11637): Added TimaKesytore provider
D/PackageManager( 2420): delete native library directory: 
D/PackageManager( 2420): return delete result to caller: 1126408696
D/AndroidRuntime(11579): Shutting down VM
D/PackageManager( 2420): returnCode: 1
D/dalvikvm(11579): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 5ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Scheme: "mms"
D/dalvikvm(11637): GC_CONCURRENT freed 3006K, 31% free 9558K/13680K, paused 4ms+2ms, total 27ms
D/dalvikvm(11637): WAIT_FOR_CONCURRENT_GC blocked 22ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (11651): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11651):  
I/ActivityManager( 2420): Killing 7018:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1816s
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux (11651): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11651):  
I/SELinux (11651):  
I/SELinux (11651): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11651): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(11651): >>>>> Normal User
E/dalvikvm(11651): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (11651): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
D/TimaKeyStoreProvider(11651): in addTimaSignatureService
D/TimaKeyStoreProvider(11651): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11651): Added TimaKesytore provider
W/ApplicationsProvider( 2961): Could not fetch usage stats
W/ApplicationsProvider( 2961): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2961): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2961): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2961): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2961): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2961): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2961): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm(11651): GC_CONCURRENT freed 3003K, 31% free 9563K/13684K, paused 4ms+2ms, total 34ms
D/dalvikvm(11651): WAIT_FOR_CONCURRENT_GC blocked 17ms
I/SELinux (11667): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11667):  
I/SELinux (11667): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11667):  
I/SELinux (11667):  
I/SELinux (11667): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11667): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11667): >>>>> Normal User
E/dalvikvm(11667): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (11667): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2420): Killing 7056:com.android.email/u0a157 (adj 15): empty for 1817s
I/dalvikvm(11667): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(11667): in addTimaSignatureService
D/TimaKeyStoreProvider(11667): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11667): Added TimaKesytore provider
D/dalvikvm(11667): GC_CONCURRENT freed 2995K, 31% free 9565K/13676K, paused 4ms+2ms, total 27ms
D/dalvikvm(11667): WAIT_FOR_CONCURRENT_GC blocked 16ms
E/SQLiteDatabase(11667): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(11667): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(11667): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(11667): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(11667): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(11667): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(11667): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(11667): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(11667): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(11667): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(11667): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(11667): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(11667): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(11667): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11667): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(11667): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(11667): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(11667): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(11667): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(11667): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(11667): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(11667): Shutting down VM
W/dalvikvm(11667): threadid=1: thread exiting with uncaught exception (group=0x41bc2c08)
E/AndroidRuntime(11667): FATAL EXCEPTION: main
E/AndroidRuntime(11667): Process: com.sec.pcw.device, PID: 11667
E/AndroidRuntime(11667): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11667): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(11667): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(11667): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(11667): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(11667): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(11667): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11667): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(11667): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(11667): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(11667): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(11667): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(11667): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(11667): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(11667): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(11667): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(11667): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(11667): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(11667): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(11667): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(11667): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(11667): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(11667): 	... 12 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2420): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2420): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2420): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2420): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2420): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2420): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2420): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2420): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2420): 	... 5 more
I/SELinux (11680): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11680):  
I/Process (11667): Sending signal. PID: 11667 SIG: 9
I/ActivityManager( 2420): Process com.sec.pcw.device (pid 11667) (adj 0) has died.
I/SELinux (11680): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11680):  
I/SELinux (11680):  
I/SELinux (11680): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11680): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11680): >>>>> Normal User
E/dalvikvm(11680): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (11680): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(11680): in addTimaSignatureService
D/TimaKeyStoreProvider(11680): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11680): Added TimaKesytore provider
D/dalvikvm(11680): GC_CONCURRENT freed 3000K, 31% free 9571K/13684K, paused 3ms+1ms, total 26ms
D/dalvikvm(11680): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/System.err(11680): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(11680): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(11680): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(11680): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(11680): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(11680): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(11680): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(11680): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(11680): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(11680): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11680): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(11680): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(11680): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(11680): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(11680): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(11680): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(11680): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(11680): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(11680): 	at libcore.io.Posix.open(Native Method)
W/System.err(11680): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(11680): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(11680): 	... 21 more
D/GalaxyFinderApplication(11680): [Slink platform] Version = 29011
D/GalaxyFinderApplication(11680): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (11694): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11694):  
I/ActivityManager( 2420): Killing 7087:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1817s
I/SELinux (11694): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11694):  
I/SELinux (11694):  
I/SELinux (11694): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11694): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(11694): >>>>> Normal User
E/dalvikvm(11694): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (11694): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(11694): in addTimaSignatureService
D/TimaKeyStoreProvider(11694): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11694): Added TimaKesytore provider
D/dalvikvm(11694): GC_CONCURRENT freed 2990K, 31% free 9573K/13680K, paused 3ms+2ms, total 25ms
D/dalvikvm(11694): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/ContextImpl(11694): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(11694): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(11694): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(11694): ContentProvider is not null
W/ResourceType(11694): No package identifier when getting value for resource number 0x00000000
I/System.out(11694): resource Id::2131361807
E/SQLiteDatabase(11694): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(11694): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(11694): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(11694): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(11694): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(11694): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(11694): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(11694): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(11694): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(11694): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(11694): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(11694): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(11694): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(11694): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(11694): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11694): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(11694): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(11694): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(11694): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(11694): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(11694): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(11694): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(11694): Shutting down VM
W/dalvikvm(11694): threadid=1: thread exiting with uncaught exception (group=0x41bc2c08)
E/AndroidRuntime(11694): FATAL EXCEPTION: main
E/AndroidRuntime(11694): Process: com.sec.android.app.shealth, PID: 11694
E/AndroidRuntime(11694): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11694): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(11694): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(11694): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(11694): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11694): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(11694): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(11694): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(11694): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(11694): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(11694): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(11694): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(11694): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(11694): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(11694): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(11694): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(11694): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(11694): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(11694): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(11694): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(11694): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(11694): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(11694): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(11694): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(11694): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHeal
```
