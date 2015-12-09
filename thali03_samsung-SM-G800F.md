#### Test 50650278d0426ce_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 6609): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42230c60, skipping init
D/dalvikvm( 6625): GC_CONCURRENT freed 2997K, 29% free 9581K/13484K, paused 4ms+1ms, total 21ms
D/dalvikvm( 6625): WAIT_FOR_CONCURRENT_GC blocked 12ms
I/SecureStorage( 6609): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)Credentials: uid 1000, gid 1000, pid 6609
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)Received function mask & code: 00000106
--------- beginning of /dev/log/system
D/ActivityThread( 6625): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6625): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ActivityManager( 2408): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6625): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/SA      ( 5780): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5780): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5780): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5674): loadAuthorityPref(): sEnableAuthority = true
I/Icing.InternalIcingCorporaProvider( 6397): Updating corpora: A: com.test.thalitest, C: MAYBE
W/ContextImpl( 6332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 6654): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6654):  
I/SELinux ( 6654): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6654):  
I/SELinux ( 6654):  
I/SELinux ( 6654): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6654): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6654): >>>>> Normal User
E/dalvikvm( 6654): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6654): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6654): in addTimaSignatureService
D/TimaKeyStoreProvider( 6654): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6654): Added TimaKesytore provider
D/dalvikvm( 6654): GC_CONCURRENT freed 3000K, 29% free 9577K/13484K, paused 3ms+7ms, total 44ms
D/dalvikvm( 6654): WAIT_FOR_CONCURRENT_GC blocked 33ms
D/CapabilityManagerService New( 6654): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 6668): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6668):  
I/ActivityManager( 2408): Killing 5299:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 6668): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6668):  
I/SELinux ( 6668):  
I/SELinux ( 6668): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6668): >>>>> Normal User
E/dalvikvm( 6668): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6668): in addTimaSignatureService
I/Icing.InternalIcingCorporaProvider( 6397): UpdateCorporaTask done [took 261 ms] updated apps [took 261 ms] 
I/ActivityManager( 2408): Killing 5735:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
D/TimaKeyStoreProvider( 6668): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6668): Added TimaKesytore provider
D/dalvikvm( 6668): GC_CONCURRENT freed 2997K, 29% free 9574K/13476K, paused 2ms+1ms, total 18ms
D/dalvikvm( 6668): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/PackageIntentReceiver( 6668): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6668): Not GearManger package! 
,I/SELinux ( 6681): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6681):  
I/ActivityManager( 2408): Killing 5546:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 6681): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6681):  
I/SELinux ( 6681):  
I/SELinux ( 6681): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6681): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6681): >>>>> Normal User
E/dalvikvm( 6681): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6681): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 6681): in addTimaSignatureService
D/TimaKeyStoreProvider( 6681): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6681): Added TimaKesytore provider
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)PID: 6609, TID: 6621
D/dalvikvm( 6681): GC_CONCURRENT freed 2994K, 29% free 9581K/13480K, paused 4ms+1ms, total 22ms
D/dalvikvm( 6681): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/MagazineService Version( 6681): Magazine-Channel: 13
D/MagazineService Version( 6681): Magazine-Provider: 13
D/MagazineService Version( 6681): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 6681): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 6681): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/MagazineService::MagazineService( 6681): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 6696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6696):  
D/MagazineService::MagazineService( 6681): [onHandleIntent] Send broadcast to (com.test.thalitest).
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9510K/10456K, paused 2ms+2ms, total 35ms
I/SELinux ( 6696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6696):  
I/SELinux ( 6696):  
I/SELinux ( 6696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6696): >>>>> Normal User
E/dalvikvm( 6696): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 6696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6696): in addTimaSignatureService
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9510K/10456K, paused 3ms+3ms, total 26ms
I/ActivityManager( 2408): Killing 5995:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/TimaKeyStoreProvider( 6696): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6696): Added TimaKesytore provider
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9510K/10456K, paused 3ms+3ms, total 26ms
I/SecureStorage( 6609): [INFO]: SPID(0x00000000)Processing data has been completed
D/dalvikvm( 6696): GC_CONCURRENT freed 3004K, 29% free 9577K/13484K, paused 3ms+1ms, total 20ms
D/dalvikvm( 6696): WAIT_FOR_CONCURRENT_GC blocked 7ms
I/PowerManagerService( 2408): [PWL] Off : 75s ago
I/PowerManagerService( 2408): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2408): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2408): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3157, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=542)
D/AndroidRuntime( 6693): 
D/AndroidRuntime( 6693): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6693): CheckJNI is OFF
D/AndroidRuntime( 6693): setted country_code = Poland
D/AndroidRuntime( 6693): setted countryiso_code = PL
D/AndroidRuntime( 6693): setted sales_code = PLS
D/AndroidRuntime( 6693): readGMSProperty: start
D/AndroidRuntime( 6693): readGMSProperty: already setted!!
D/AndroidRuntime( 6693): readGMSProperty: end
D/AndroidRuntime( 6693): addProductProperty: start
D/dalvikvm( 6693): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6693): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6693): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6693): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6693): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 6716): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6716):  
I/ActivityManager( 2408): Killing 5750:com.sec.android.soagent/u0a38 (adj 15): empty #43
I/SELinux ( 6716): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6716):  
I/SELinux ( 6716):  
I/SELinux ( 6716): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6716): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6716): >>>>> Normal User
E/dalvikvm( 6716): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
E/SELinux ( 6716): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6716): in addTimaSignatureService
D/TimaKeyStoreProvider( 6716): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6716): Added TimaKesytore provider
E/memtrack( 6693): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6693): failed to load memtrack module: -2
D/dalvikvm( 6716): GC_CONCURRENT freed 2990K, 29% free 9584K/13480K, paused 4ms+1ms, total 22ms
D/dalvikvm( 6716): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/KidsPlatformStub( 6716): Package not found : com.sec.android.app.kidshome
D/dalvikvm( 6693): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 6728): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6728):  
I/ActivityManager( 2408): Killing 6082:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
I/SELinux ( 6728): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6728):  
I/SELinux ( 6728):  
I/SELinux ( 6728): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6728): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6728): >>>>> Normal User
E/dalvikvm( 6728): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
E/SELinux ( 6728): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/AndroidRuntime( 6693): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 6728): in addTimaSignatureService
D/TimaKeyStoreProvider( 6728): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6728): Added TimaKesytore provider
D/dalvikvm( 6728): GC_CONCURRENT freed 2994K, 29% free 9577K/13480K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6728): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2408): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2408): mDVFSHelper.acquire()
I/SELinux ( 6742): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6742):  
D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6693): Shutting down VM
D/dalvikvm( 6693): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6746): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6746):  
I/SELinux ( 6742): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6742):  
I/SELinux ( 6742):  
I/SELinux ( 6742): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6742): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6742): >>>>> Normal User
E/dalvikvm( 6742): >>>>> com.test.thalitest [ userId:0 | appId:10523 ]
I/ActivityManager( 2408): Killing 5828:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
E/SELinux ( 6742): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6742): in addTimaSignatureService
D/TimaKeyStoreProvider( 6742): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6742): Added TimaKesytore provider
I/SELinux ( 6746): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6746):  
I/SELinux ( 6746):  
I/SELinux ( 6746): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6746): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6746): >>>>> Normal User
E/dalvikvm( 6746): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
E/SELinux ( 6746): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/Icing   ( 3157): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
D/TimaKeyStoreProvider( 6746): in addTimaSignatureService
D/TimaKeyStoreProvider( 6746): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6746): Added TimaKesytore provider
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
I/SQLiteSecureOpenHelper( 4182): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4182): getDatabaseLocked(b,b,pwd)...
D/dalvikvm( 6742): GC_CONCURRENT freed 2998K, 29% free 9573K/13480K, paused 2ms+1ms, total 20ms
D/dalvikvm( 6742): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 6746): GC_CONCURRENT freed 3002K, 29% free 9574K/13480K, paused 3ms+1ms, total 30ms
D/dalvikvm( 6746): WAIT_FOR_CONCURRENT_GC blocked 26ms
,V/WebViewChromium( 6742): Binding Chromium to the background looper Looper (main, tid 1) {422332b8}
I/chromium( 6742): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/UMC:Core( 6746): onCreate(): 
,I/BrowserProcessMain( 6742): Initializing chromium process, renderers=0
,W/chromium( 6742): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6742): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6742): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6742): loaded /system/lib/egl/libGLESv2_mali.so
,I/Icing   ( 3157): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,I/Mali    ( 6742): Mali API Version : 401
,I/Mali    ( 6742): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6742): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6742): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6742): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6742): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6742): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6742): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2408): tr p:6742,o:f
,D/USER_AGENT( 6746): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,W/dalvikvm( 6742): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6742): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,I/dalvikvm( 6742): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6742): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 6742): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6742): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6742): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6742): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6742): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6742): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6742): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6742): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6742): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2408): semi p:6742,o:f
,D/[SAMSUNG SMARCART NATIVE]( 6746): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6746): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/TZ_CCM_C_GetFunctionList: ( 6746): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 6746): FINISHED: initialize rv:0
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6742): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6742): Enabling debug mode 0
,W/AwContents( 6742): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2408): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  tag : ACTIVITY_RESUME_BOOSTER@4,
W/ActivityManager( 2408): mDVFSHelper.release()
W/AwContents( 6742): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2408): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 6742): showStatusIcon on inactive InputConnection
,D/dalvikvm( 6746): GC_CONCURRENT freed 1862K, 21% free 10779K/13544K, paused 5ms+2ms, total 35ms,
,D/UMC:SecurityUtils( 6746): Loaded server certificates: 0,
,D/UMC:SecurityUtils( 6746): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6746): New Flow
D/TimaService( 2408): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2408): TIMA: in getTimaVersion
I/        ( 2408): CCM JNI: In ccm_register_for_default_cert
I/        ( 2408): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2408): &ctx = 0x7bcd2618
I/TLC_TZ_CCM: ( 2408): creating new ccm context...
I/TLC_TZ_CCM: ( 2408): initializing ccm context...
I/TLC_TZ_CCM: ( 2408): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2408): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2408): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2408): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2408): root = 0, root_len = 1
I/TZ: client_server_communication( 2408): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2408): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2408): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2408): Client_Server_Open was called
I/TZ: client_server_communication( 2408): IClientServer::IClientServer()
I/TZ: client_server_communication( 2408): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2508): creating new ccm context...
I/TZ_CCM_SERVER( 2508): initializing ccm context...
I/TZ_CCM_SERVER( 2508): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2508): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2508): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2508): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2508): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2508): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2508): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2508): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2508): device_id = 0x0
I/TZ: mc_tlc_communication( 2508): tlc_open() was called
I/TZ: mc_tlc_communication( 2508): Opening MobiCore device
I/TZ: mc_tlc_communication( 2508): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2508): Opening the session
,I/TZ: mc_tlc_communication( 2508): tlc_open() succeeded
,I/TZ: client_server_communication( 2408): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2408): ctx = 0x85ce9f80, comm = 0x7bb5d3d0, sendmsg = 0x80fe9698, recvmsg = 0x80fee298
I/TZ_init: ( 2408): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,E/Parcel  ( 2408): nm 19456
E/TZ_init: ( 2408): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2408): trustlet initialization failed
,I/TZ_init: ( 2408): TZ_init_START...
,I/TZ_init: ( 2408): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,E/Parcel  ( 2408): nm 19456
,I/TZ_init: ( 2408): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2408): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,E/Parcel  ( 2408): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2408): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: ( 2408): Exercising TZ_CCM_register_default_TLC
,I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
E/Parcel  ( 2408): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2408): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2408): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2408): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
E/Parcel  ( 2408): nm 19456
,I/TZ: client_server_communication( 2408): Client_Server_Close was called
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2508): tlc_close() was called
,I/TZ: mc_tlc_communication( 2508): Closing the session
,I/TZ: mc_tlc_communication( 2508): Free WSM
,I/TZ: mc_tlc_communication( 2508): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2508): tlc_close() succeeded
,I/TZ: client_server_communication( 2408): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6746): TIMA service call for password change success!!
,D/UMC:AdminManager( 6746): init - start
,D/UMC:AdminManager( 6746): loadAdmins,
,D/UMC:AdminManager( 6746): removeOutOfSyncProxyAdmins,
D/UMC:AdminManager( 6746): startPolicyHandlers
I/UMC:TestPolicyHandler( 6746): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6746): init - end
,V/UMC:AlarmHandler( 6746): Enter loadList
,D/EnterpriseDeviceManagerService( 2408): Creating context as user 0
,D/SPPApp  ( 6746): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6746): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6800): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6800):  
,I/ActivityManager( 2408): Killing 6102:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,I/SELinux ( 6800): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6800):  
I/SELinux ( 6800):  
,I/SELinux ( 6800): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/JsMessageQueue( 6742): Set native->JS mode to OnlineEventsBridgeMode
,E/SELinux ( 6800): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6800): >>>>> Normal User
,E/dalvikvm( 6800): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6800): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6800): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6800): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6800): Added TimaKesytore provider
,D/dalvikvm( 6800): GC_CONCURRENT freed 2999K, 29% free 9581K/13484K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 6800): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/ApplicationPromenada( 6800): Application OnCreate start
,D/ApplicationPromenada( 6800): Application OnCreate po on Create
D/CrashReporter( 6800): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42239468
D/CrashReporter( 6800): Swaping uncaught exception handler
,D/ApplicationPromenada( 6800): Application OnCreate App Loader start
,D/ApplicationPromenada( 6800): Application OnCreate App Loader finish
,D/dalvikvm( 6742): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4222bff8
,D/dalvikvm( 6742): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4222bff8
D/jxcore_app_log( 6742): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030911560
,D/JX-Cordova( 6742): jxcore cordova android initializing
,I/dalvikvm( 6742): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 6742): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6742): VFY: replacing opcode 0x6e at 0x0045
,D/p2.ApplicationLoader( 6800): ############################## cached apps: 
,V/WebViewChromium( 6800): Binding Chromium to the background looper Looper (main, tid 1) {42235280}
,I/chromium( 6800): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6800): Initializing chromium process, renderers=0
,W/chromium( 6800): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6800): loaded /system/lib/egl/libEGL_mali.so
D/dalvikvm( 6742): GC_CONCURRENT freed 1296K, 17% free 11352K/13548K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 6742): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/libEGL  ( 6800): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6800): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6800): Mali API Version : 401
,I/Mali    ( 6800): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6800): Application OnCreate Finish
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ActivityManager( 2408): Killing 6117:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/PackageBroadcastService( 3157): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3157): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService( 2408): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  tag : ACTIVITY_RESUME_BOOSTER@8
,D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3157): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3157): Submit a task: k
,D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 3157): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Finsky  ( 3722): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/GassUtils( 3157): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3157): Found info for package com.test.thalitest in db.
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 72804 latestRequest time : 1449681180286 current time : 1449681253090
,D/dalvikvm( 6742): GC_CONCURRENT freed 1919K, 16% free 14977K/17808K, paused 2ms+2ms, total 72ms
,D/dalvikvm( 6742): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3989): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6800): GC_CONCURRENT freed 1763K, 20% free 10827K/13488K, paused 3ms+9ms, total 52ms
,I/VacuumService( 2733): Vacuum at: now=1449681253432 tag=VacuumService
,D/dalvikvm( 6742): GC_FOR_ALLOC freed 5364K, 29% free 16210K/22712K, paused 46ms, total 46ms
,I/PhenotypeConfigurator( 2733): Scheduling Phenotype for one-off execution 1787 seconds from now (1449681254142)
,I/Icing   ( 3157): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/GetConfigurationSnapshotOperation( 2733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/dalvikvm( 6800): GC_CONCURRENT freed 2364K, 24% free 10444K/13704K, paused 3ms+2ms, total 53ms
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2733): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2733): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2408): GC_EXPLICIT freed 24962K, 71% free 25441K/87640K, paused 15ms+28ms, total 373ms
,W/ResourceType( 6800): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6800): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6800): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6800): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6800): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6800): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6800): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6800): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6800): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6800): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6800): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6800): 	at java.lang.Thread.run(Thread.java:841)
,I/Icing   ( 3157): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/LocationManagerService( 2408): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2733): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2733): Thread-116(HTTPLog):isShipBuild true
,I/System.out( 2733): Thread-116(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 6742): GC_CONCURRENT freed 6707K, 31% free 17672K/25304K, paused 2ms+10ms, total 74ms
,D/dalvikvm( 6742): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 6742): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 2733): GC_CONCURRENT freed 1622K, 19% free 11807K/14404K, paused 5ms+8ms, total 84ms
,D/dalvikvm( 6742): GC_FOR_ALLOC freed 1421K, 32% free 17356K/25304K, paused 42ms, total 51ms
,I/dalvikvm-heap( 6742): Grow heap (frag case) to 21.345MB for 3688532-byte allocation
,D/dalvikvm( 6742): GC_FOR_ALLOC freed 2416K, 36% free 18542K/28908K, paused 44ms, total 44ms
,D/dalvikvm( 6800): GC_CONCURRENT freed 2128K, 25% free 10320K/13704K, paused 2ms+3ms, total 54ms
,W/jxcore-log( 6742): Initializing JXcore engine
,W/jxcore-log( 6742): JXcore engine is ready
,W/jxcore-log( 6742): Starting JXcore engine
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 360, Delta = 20
,D/LocationManagerService( 2408): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2408): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/jxcore-log( 6742): Platform android
W/jxcore-log( 6742): 
,W/jxcore-log( 6742): Process ARCH arm
W/jxcore-log( 6742): 
,D/p2.ApplicationLoader( 6800): Process time: 3984
,D/p2.ApplicationLoader( 6800): ##############################  apps after loading: 
,D/dalvikvm( 6800): GC_CONCURRENT freed 2141K, 27% free 10102K/13704K, paused 2ms+2ms, total 33ms
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/jxcore-log( 6742): JXcore Cordova bridge is ready!
I/jxcore-log( 6742): 
,W/jxcore-log( 6742): JXcore engine is started
,I/chromium( 6742): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6742): Toggling radios to true
I/jxcore-log( 6742): 
,D/BluetoothAdapter( 6742): enable(): BT is already enabled..!
,I/WifiManager( 6742): packageName : com.test.thalitest
I/WifiManager( 6742): setWifiEnabled : true
,I/WifiService( 2408): setWifiEnabled: true pid=6742, uid=10523
,W/ActivityManager( 2408): Permission Denial: getCurrentUser() from pid=6742, uid=10523 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2408): Failed getting userId using ActivityManagerNative
W/WifiService( 2408): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6742, uid=10523 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2408): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2408): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2408): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2408): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2408): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2408): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2408): disconnect: pid=6742, uid=10523
I/wpa_supplicant( 3959): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6742): Radios toggled
I/jxcore-log( 6742): 
,I/wpa_supplicant( 3959): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3959): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3959): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3959): First Scan Start
W/Settings( 2408): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3959): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2408): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2408): InactiveState{ what=143375 }
D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
D/ConnectivityService( 2408): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3959): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3959): Skip scan - already scanning
D/ConnectivityService( 2408): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2408): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2408): InactiveState{ what=143375 }
E/ConnectivityService( 2408): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2408): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2408): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2408): Attempting to switch to mobile
,D/ConnectivityService( 2408): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 6856): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6856):  
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/SELinux ( 6856): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6856):  
I/SELinux ( 6856):  
I/SELinux ( 6856): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6856): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6856): >>>>> Normal User
,E/dalvikvm( 6856): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6856): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2408): route cmd failed: 
W/NetworkManagementService( 2408): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2408): '
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2408): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2408): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-66ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2408): Error! unhandled message{ when=-64ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/WifiStateMachine( 2408): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 6856): in addTimaSignatureService
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2408): android_net_utils_resetConnections in env=0x77f32250 clazz=0x62300001 iface=wlan0 mask=0x3
D/ConnectivityService( 2408): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 6856): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6856): Added TimaKesytore provider
,E/SPPClientService( 5514): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5514): [e] exceptionCaught(). NET_TIMEOUT
,V/NativeCrypto( 2844): Read error: ssl=0x7bdb1100: I/O error during system call, Connection timed out
,E/SPPClientService( 5514): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,V/NativeCrypto( 2844): SSL shutdown failed: ssl=0x7bdb1100: I/O error during system call, Broken pipe
,E/SPPClientService( 5514): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5514): [b] ResponseMap empty
,D/dalvikvm( 6856): GC_CONCURRENT freed 2985K, 29% free 9591K/13484K, paused 4ms+10ms, total 72ms
,D/dalvikvm( 6856): WAIT_FOR_CONCURRENT_GC blocked 65ms
,D/ConnectivityService( 2408): handleInetConditionChange: no active default network - ignore,
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): updateIfacesLocked()
V/NetworkStats( 2408): performPollLocked(flags=0x1)
V/NetworkStats( 2408): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 25ms
,I/System.out( 6856): Inside WakeupProvider
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,I/System.out( 6856): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6856): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6856): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6856): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
I/ActivityManager( 2408): Killing 5284:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,D/DialogFlow( 6856): initQueue()
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2408): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2408): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2408): updateDataUsageMap
,D/CaptivePortalTracker( 2408): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
D/ConnectivityService( 2408): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4726): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): noConnectivity : true,
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection...,
,I/SELinux ( 6885): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6885):  
,I/SELinux ( 6885): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6885):  
I/SELinux ( 6885):  
,I/SELinux ( 6885): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6885): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6885): >>>>> Normal User
,E/dalvikvm( 6885): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6885): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6885): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6885): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6885): Added TimaKesytore provider,
,D/dalvikvm( 6885): GC_CONCURRENT freed 3007K, 29% free 9575K/13484K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 6885): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/wpa_supplicant( 3959): nl80211: Received scan results (7 BSSes)
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
D/Tethering( 2408): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3959): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3959): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/ActivityManager( 2408): Killing 6146:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3959): Associated with C0.AA.48
I/wpa_supplicant( 3959): freq(2412) increment count 2
,I/wpa_supplicant( 3959): meet head of list.
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3959): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3959): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/WifiNative( 2408): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6899): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6899):  
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
I/SELinux ( 6899): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6899):  
I/SELinux ( 6899):  
I/SELinux ( 6899): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6899): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6899): >>>>> Normal User
E/dalvikvm( 6899): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
E/SELinux ( 6899): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6899): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6899): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6899): Added TimaKesytore provider
,D/dalvikvm( 6899): GC_CONCURRENT freed 2993K, 29% free 9583K/13480K, paused 3ms+1ms, total 21ms,
,D/dalvikvm( 6899): WAIT_FOR_CONCURRENT_GC blocked 14ms,
,I/ActivityManager( 2408): Killing 6217:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,I/SELinux ( 6914): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6914):  
,I/dhcpcd  ( 6911): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6911): bssid match,
I/SELinux ( 6914): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6914):  
I/SELinux ( 6914):  
,I/SELinux ( 6914): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6914): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6914): >>>>> Normal User
,E/dalvikvm( 6914): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6914): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6914): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6914): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6914): Added TimaKesytore provider
,D/dalvikvm( 6914): GC_CONCURRENT freed 2997K, 29% free 9573K/13476K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 6914): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/KLMS-2.3.201 : ( 6914): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 6914): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681258882
,I/KLMS-2.3.201 : ( 6914): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2408): Killing 6290:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 6930): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6930):  
,I/SELinux ( 6930): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6930):  
I/SELinux ( 6930):  
,I/SELinux ( 6930): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6930): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6930): >>>>> Normal User
,E/dalvikvm( 6930): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 6930): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6930): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6930): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6930): Added TimaKesytore provider
D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 6930): GC_CONCURRENT freed 2993K, 29% free 9580K/13476K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6930): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/SO_AGENT( 6930): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 6930): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5780): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5780): [BDLM] already registered in spp
,I/SA      ( 5780): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5780): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5780): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5780): [OR] == isSIMCardReady false ==
,I/SA      ( 5780): [SCU] == networkStateCheck == false
,I/SA      ( 5780): [OR] onReceive END
I/ActivityManager( 2408): Killing 6313:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SELinux ( 6942): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6942):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 10% free 9510K/10456K, paused 2ms+3ms, total 33ms
,I/SELinux ( 6942): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6942):  
I/SELinux ( 6942):  
,I/SELinux ( 6942): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6942): >>>>> Normal User
,E/dalvikvm( 6942): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6942): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9510K/10456K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 6942): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6942): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6942): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9510K/10456K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 6942): GC_CONCURRENT freed 2997K, 29% free 9578K/13480K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 6942): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/sCloudBackupApp( 6942): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6942): Other Intent
I/ActivityManager( 2408): Killing 6355:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 6955): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6955):  
,I/SELinux ( 6955): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6955):  
I/SELinux ( 6955):  
,I/SELinux ( 6955): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6955): >>>>> Normal User
,E/dalvikvm( 6955): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 6955): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6955): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6955): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6955): Added TimaKesytore provider
,D/dalvikvm( 6955): GC_CONCURRENT freed 2990K, 29% free 9578K/13476K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 6955): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 6955): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 6955): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5311): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 6955): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5311): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 6955): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5311): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2408): Killing 5560:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5843): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5843): getCountryCode(): countryCode = PL
D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5843): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5843): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5843): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 6967): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6967):  
,I/SELinux ( 6967): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6967):  
I/SELinux ( 6967):  
,I/SELinux ( 6967): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6967): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6967): >>>>> Normal User
,E/dalvikvm( 6967): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 6967): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6967): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6967): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6967): Added TimaKesytore provider
,D/dalvikvm( 6967): GC_CONCURRENT freed 2994K, 29% free 9579K/13480K, paused 12ms+1ms, total 29ms
,D/dalvikvm( 6967): WAIT_FOR_CONCURRENT_GC blocked 10ms
,V/WebViewChromium( 6967): Binding Chromium to the background looper Looper (main, tid 1) {42232350}
,I/chromium( 6967): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6967): Initializing chromium process, renderers=0
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,W/chromium( 6967): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/WifiStateMachine( 2408): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/libEGL  ( 6967): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6967): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2408): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/libEGL  ( 6967): loaded /system/lib/egl/libGLESv2_mali.so
,D/WifiStateMachine( 2408): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2408): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2408): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2408): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/Mali    ( 6967): Mali API Version : 401
I/Mali    ( 6967): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
D/ConnectivityService( 2408): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2408): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2408): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2408): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): updateIfacesLocked()
,V/NetworkStats( 2408): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,W/GAV2    ( 6967): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 15ms
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 6967): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 6967): Starting up...
,I/iu.Environment( 5911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 2408): Killing 4836:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5114): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5114): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5114): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42268900
,I/SELinux ( 7041): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7041):  
,I/SELinux ( 7041): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7041):  
I/SELinux ( 7041):  
,I/SELinux ( 7041): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7041): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7041): >>>>> Normal User
,E/dalvikvm( 7041): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7041): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7041): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7041): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7041): Added TimaKesytore provider
,D/dalvikvm( 7041): GC_CONCURRENT freed 2991K, 29% free 9589K/13484K, paused 4ms+1ms, total 20ms
,D/dalvikvm( 7041): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/Tethering( 2408): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2408): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2408): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4726): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,I/ActivityManager( 2408): Killing 6267:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7060): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7060):  
,I/SELinux ( 7060): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7060):  
I/SELinux ( 7060):  
,I/SELinux ( 7060): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7060): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7060): >>>>> Normal User
,E/dalvikvm( 7060): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7060): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7068): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7068):  
,D/TimaKeyStoreProvider( 7060): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7060): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7060): Added TimaKesytore provider
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection...
,W/ActivityManager( 2408): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7068): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7068):  
I/SELinux ( 7068):  
I/SELinux ( 7068): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7068): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7068): >>>>> Normal User
E/dalvikvm( 7068): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7068): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
I/ActivityManager( 2408): Killing 6413:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7068): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7068): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7068): Added TimaKesytore provider,
,D/dalvikvm( 7060): GC_CONCURRENT freed 3002K, 30% free 9573K/13484K, paused 4ms+1ms, total 37ms,
,D/dalvikvm( 7060): WAIT_FOR_CONCURRENT_GC blocked 28ms,
,D/BadgeProvider( 7060): onCreate,
,D/BadgeProvider( 7060): DatabaseHelper,
,D/BadgeProvider( 7060): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,D/dalvikvm( 7068): GC_CONCURRENT freed 2999K, 29% free 9580K/13484K, paused 5ms+1ms, total 56ms,
,D/dalvikvm( 7068): WAIT_FOR_CONCURRENT_GC blocked 39ms,
D/BadgeProvider( 7060): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7060): sendNotify, [notify] : null
D/BadgeProvider( 7060): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7060): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7060): update, [UpdateCount] : 1,
,D/Launcher.Model( 2777): reloadBadges entered.,
,D/PackageManager( 2408): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/hcjo    ( 5932): AutoUpdateManager:IDLE:execute,
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE,
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 154340,
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : true,
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null,
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: CONNECTED,
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state,
,D/InitializeManagerStateMachine( 5932): execute::IDLE:EXECUTE
,E/SPPClientService( 5514): [[SystemStateMonitorService]] No Active Internet
,D/InitializeManagerStateMachine( 5932): exit::IDLE
,D/InitializeManagerStateMachine( 5932): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5932): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5932): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5932): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5932): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5932): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5932): entry::SUCCESS
,D/hcjo    ( 5932): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5932): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5932): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5932): exit::SUCCESS
,D/InitializeManagerStateMachine( 5932): entry::IDLE
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5514): [[PushClientService]] <<--- deInitPushClientService  END  --->>,
,E/SPPClientService( 5514): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19,
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state,
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast,
I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408,
,E/SPPClientService( 5514): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false,
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.,
,E/SPPClientService( 5514): [g] getNetMCC return empty string,
,I/KLMS-2.3.201 : ( 6914): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,I/KLMS-2.3.201 : ( 6914): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681261735,
,I/KLMS-2.3.201 : ( 6914): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false,
,D/SO_AGENT( 6930): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
I/SO_AGENT( 6930): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 3299): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert,
D/GalaxyFinderApplication( 3299): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3299): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3299): [Slink platform] The state of Slink geocode service is true,
,I/GallerySearchProvider( 3427): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query,
I/SELinux ( 7095): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7095):  
I/SELinux ( 7095): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7095):  
I/SELinux ( 7095):  
I/SELinux ( 7095): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7095): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7095): >>>>> Normal User
E/dalvikvm( 7095): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7095): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7095): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7095): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7095): Added TimaKesytore provider
,D/dalvikvm( 2718): GC_EXPLICIT freed 336K, 26% free 10045K/13468K, paused 6ms+6ms, total 52ms
,D/PackageManager( 2408): [MSG] SEND_PENDING_BROADCAST,
,D/PackageManager( 2408): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@44708290, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}],
,D/dalvikvm( 7095): GC_CONCURRENT freed 2985K, 29% free 9591K/13480K, paused 3ms+1ms, total 29ms,
,D/dalvikvm( 7095): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "sms",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2408): Reconfiguring input devices.  changes=0x00000010,
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection - timeout,
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection...
,D/RegisteredServicesCache( 2758): empty dynamic service,
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "smsto",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "mms",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "mmsto",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/PackageManager( 2408):   Scheme: "sms"
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "smsto",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "mms",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2408):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2408):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2408):   Scheme: "mmsto",
I/PackageManager( 2408): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SA      ( 5780): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,I/SA      ( 5780): [BDLM] already registered in spp
I/SA      ( 5780): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5780): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,I/SA      ( 5780): [TPMU]  strSIMState ,	:SIM_STATE_UNKNOWN
,I/SA      ( 5780): [OR] == isSIMCardReady false ==,
,I/SA      ( 5780): [SCU] == networkStateCheck == true,
I/SA      ( 5780): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5780): isChinaCountryCode : false
,I/SA      ( 5780): [OR] == networkStateCheck true ==,
,I/SA      ( 5780): [OR] GetMyCountryZoneTask,
,I/SA      ( 5780): [OR] onReceive END,
,I/SA      ( 5780): [SRS] prepareGetMyCountryZone,
,I/SA      ( 5780): [TPMU]  strSIMState ,	:SIM_STATE_UNKNOWN
,I/SA      ( 5780): [SSP] query invoked,
D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled,
,I/SCloudBackupReceiver( 6942): Other Intent,
,D/dalvikvm( 2408): GC_EXPLICIT freed 3096K, 71% free 25481K/87640K, paused 13ms+20ms, total 244ms,
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
,D/Headlines( 5843): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5843): getCountryCode(): countryCode = PL,
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5843): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() reponse : false,
D/HeadlinesCardManager( 5843): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5843): requestUpdateNewsWelcomeCard !!! no welcome card,
,I/SA      ( 5780): [TPMU] GetMccFromDB : null
,I/SA      ( 5780): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5780): [TPM] isNoProxy(default) : true
,I/SA      ( 5780): [RC New] Execute method=[GET] start
,I/HarmonyEASService( 2408): Updating for all 1
,I/iu.Environment( 5911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/SELinux ( 7115): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7115):  
D/QuickConnect[1.1][2] ( 5114): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5114): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5114): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42268900
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,I/SELinux ( 7115): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7115):  
I/SELinux ( 7115):  
,I/SELinux ( 7115): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7115): >>>>> Normal User
,E/dalvikvm( 7115): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7115): in addTimaSignatureService
,I/System.out( 6899): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/TimaKeyStoreProvider( 7115): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7115): Added TimaKesytore provider
,D/hcjo    ( 5932): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5932): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5932): exit::IDLE
,D/InitializeManagerStateMachine( 5932): entry::NETWORK_CHECK
I/System.out( 6899): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 6899): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/InitializeManagerStateMachine( 5932): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5932): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5932): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5932): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5932): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5932): entry::SUCCESS
,D/hcjo    ( 5932): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5932): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5932): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5932): exit::SUCCESS
,D/InitializeManagerStateMachine( 5932): entry::IDLE
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 156180
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 7115): GC_CONCURRENT freed 3002K, 29% free 9578K/13484K, paused 4ms+4ms, total 26ms
,D/dalvikvm( 7115): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 5514): GC_CONCURRENT freed 1970K, 23% free 10448K/13472K, paused 20ms+3ms, total 97ms
,V/KVNProvider( 7115): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7115): getFindoCursor query string : 
,I/Icing.InternalIcingCorporaProvider( 6397): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,V/KVNProvider( 7115): getTagSearchCursor() tagSearchCursor count : 0
,I/SELinux ( 7132): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7132):  
,I/System.out( 6899): AsyncTask #1 calls detatch()
,I/SELinux ( 7132): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7132):  
I/SELinux ( 7132):  
,I/SELinux ( 7132): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7132): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7132): >>>>> Normal User
,E/dalvikvm( 7132): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
,E/SELinux ( 7132): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): stay LED for fully charged
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
W/System.err( 6899): com.sec.android.fota.osp.http.RestClientException
W/System.err( 6899): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6899): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6899): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6899): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 6899): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6899): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6899): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6899): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6899): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 6899): Caused by: java.lang.NullPointerException
W/System.err( 6899): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 6899): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6899): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6899): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6899): 	... 8 more
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/TimaKeyStoreProvider( 7132): in addTimaSignatureService
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3989): Disconnected process message: 10
I/Icing.InternalIcingCorporaProvider( 6397): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,D/TimaKeyStoreProvider( 7132): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7132): Added TimaKesytore provider
I/ActivityManager( 2408): Killing 6286:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
I/ActivityManager( 2408): Killing 5957:com.android.calendar/u0a144 (adj 15): empty #43
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ApplicationsProvider( 2966): Could not fetch usage stats
W/ApplicationsProvider( 2966): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2966): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2966): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2966): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2966): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2966): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2966): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2966): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2966): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2966): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 7132): GC_CONCURRENT freed 2993K, 29% free 9574K/13476K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7132): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/FileShare-Server( 7132): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/SELinux ( 7145): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7145):  
I/ActivityManager( 2408): Killing 6235:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7145): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7145):  
I/SELinux ( 7145):  
,I/SELinux ( 7145): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7145): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7145): >>>>> Normal User
,E/dalvikvm( 7145): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 7145): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7145): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7145): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7145): Added TimaKesytore provider
,E/WifiStateMachine( 2408): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 7145): GC_CONCURRENT freed 3003K, 29% free 9573K/13484K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7145): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/BezelQuickConnect( 5126): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5126): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,D/PackageBroadcastService( 3157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/ActivityManager( 2408): Killing 6132:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SA      ( 5780): [RC New] [v2liruge] api execute + 842
,I/SA      ( 5780): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5780): AsyncTask #2 calls detatch()
,I/SA      ( 5780): [TPMU] getNetworkMcc : 
,I/SA      ( 5780): [SCU] saveMccToPreferece Start
,I/SA      ( 5780): [SCU] RegionMCC : 260
,I/SA      ( 5780): [SSP] query invoked
,I/SA      ( 5780): [TPMU] GetMccFromDB : null
I/SA      ( 5780): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5780): [SCU] saveMccToPreferece End
I/SA      ( 5780): [RC New] executeRequest [v2liruge] end. 879
,I/SA      ( 5780): [RC New] Execute end
I/SA      ( 5780): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5780): [OR] GetMyCountryZoneTask Success
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2408): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SPPClientService( 5514): [b] __InitReply__
,I/Icing   ( 3157): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
I/Icing   ( 3157): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
I/ActivityManager( 2408): Killing 6170:com.google.android.music:main/u0a125 (adj 15): empty #43
I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2408): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2408) eventTime = 158047
D/PowerManagerService( 2408): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408 (0x0)
D/PowerManagerService( 2408): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2408, ws=WorkSource{1000}) (elapsedTime=3448)
I/GAV2    ( 6967): Thread[GAThread,5,main]: No campaign data found.
D/SSRMv2:SIOP( 2408): SIOP:: AP = 370, Delta = 10
,W/WifiP2pStateTracker( 2408): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2408): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2408):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2408): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2408): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6581): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6581): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6581): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6581): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6581): [ensureRegistration] - No Samsung account
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3722): [190] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3722): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2408): waitForAlarm result :8
D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5843): Breath 7385 latestRequest time : 1449681262904 current time : 1449681270289
,D/CaptivePortalTracker( 2408): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2408): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 2408): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2408): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2408): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2408): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2408): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2408): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5932): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5932): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5932): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5932): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5932): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5932): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5932): entry::IDLE
,I/jxcore-log( 6742): Test app app.js loaded
I/jxcore-log( 6742): 
,I/chromium( 6742): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PreloadUpdateManagerStateMachine( 5932): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5932): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5932): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5932): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5932): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5932): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5932): entry::IDLE
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3989): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 5,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 350, Delta = -20,
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{42e6f6b0 u0 com.sec.spp.push/.PushClientService},
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 105s ago,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3989): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = -20,
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3989): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 6,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3989): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2408): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :4,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5843): Breath 54702 latestRequest time : 1449681262904 current time : 1449681317606
,I/SELinux ( 7420): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7420):  
,I/SELinux ( 7420): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7420):  
I/SELinux ( 7420):  
,I/SELinux ( 7420): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7420): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
E/dalvikvm( 7420): >>>>> Normal User
,E/dalvikvm( 7420): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 7420): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
,D/TimaKeyStoreProvider( 7420): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7420): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7420): Added TimaKesytore provider
,D/dalvikvm( 7420): GC_CONCURRENT freed 3001K, 29% free 9574K/13480K, paused 3ms+2ms, total 31ms,
,D/dalvikvm( 7420): WAIT_FOR_CONCURRENT_GC blocked 27ms,
,E/SPPClientService( 7420): ============PushLog. commonIsShipBuild. stop!,
,E/SPPClientService( 7420): [PushClientApplication] Push log off : This is Ship build version,
,D/SPPClientService( 7420): PushLog.txt file is not deleted.,
D/SPPClientService( 7420): PushLog.txt file is not deleted.
,D/SPPClientService( 7420): ============PushLog. stop!,
,I/ActivityManager( 2408): Killing 6524:com.android.defcontainer/u0a6 (adj 15): empty #43,
,E/SPPClientService( 5514): [b] __PingReply__,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2408): waitForAlarm result :8,
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5843): Breath 67413 latestRequest time : 1449681262904 current time : 1449681330317,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3989): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2408): !@Sync 7,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3989): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2408): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2408): waitForAlarm result :8,
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 97388 latestRequest time : 1449681262904 current time : 1449681360293,
,E/Watchdog( 2408): !@Sync 8,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3989): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2408): waitForAlarm result :8,
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5843): Breath 127410 latestRequest time : 1449681262904 current time : 1449681390314,
,D/Headlines( 5843): stop ,
,D/Headlines( 5843): Breath.onDestroy : ,
,I/ActivityManager( 2408): Killing 6419:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,E/Watchdog( 2408): !@Sync 9,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2408): initializing...,
I/TLC_TIMA_PKM_initialize( 2408): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2408): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2408): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2408): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2408): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2408): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2408): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2408): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2408): device_id = 0x0
,I/TZ: mc_tlc_communication( 2408): tlc_open() was called
,I/TZ: mc_tlc_communication( 2408): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2408): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2408): Opening the session,
,I/TZ: mc_tlc_communication( 2408): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2408): Trustlet response is completed
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3989): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2408): [PWL] Off : 275s ago,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3989): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2408): !@Sync 11,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :4,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8089): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8089):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9510K/10456K, paused 3ms+10ms, total 100ms
,I/SELinux ( 8089): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8089):  
I/SELinux ( 8089):  
,I/SELinux ( 8089): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8089): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8089): >>>>> Normal User
,E/dalvikvm( 8089): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8089): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9510K/10456K, paused 3ms+4ms, total 40ms
,D/TimaKeyStoreProvider( 8089): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8089): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8089): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9510K/10456K, paused 4ms+5ms, total 38ms
,D/dalvikvm( 8089): GC_CONCURRENT freed 3015K, 30% free 9562K/13480K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 8089): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/ActivityManager( 2408): Killing 6553:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 12
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2408): GC_CONCURRENT freed 3858K, 71% free 25536K/87640K, paused 24ms+21ms, total 282ms
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3989): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2408): !@Sync 13
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/jxcore-log( 6742): Toggling radios to false
I/jxcore-log( 6742): 
,I/WifiManager( 6742): packageName : com.test.thalitest
,D/BluetoothAdapterService(1109574224)( 3989): unRegister RemoteMessageListener
,D/HeadsetService( 3989): registerMessageListener
,D/HeadsetStateMachine( 3989): Disconnected process message: 80
,D/BluetoothAdapterState( 3989): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 3989): Bluetooth adapter state changed: 12-> 13
,D/HeadsetStateMachine( 3989): processUnRegisterMessageListener : 2
,D/BluetoothAdapterService( 3989): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3989): updateAdapterState state is 13
,I/WifiManager( 6742): setWifiEnabled : false
,I/BluetoothPbapService( 3989): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 3989): bta_jv_rfcomm_stop_server
,D/BluetoothPbap( 2828): Proxy object disconnected
D/BluetoothAdapterService( 3989): Broadcasting updateAdapterState() to 1 receivers.
,I/WifiService( 2408): setWifiEnabled: false pid=6742, uid=10523
,D/BluetoothAdapterService( 3989): Autoconnection is available 
D/BluetoothAdapterService( 3989): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 3989): terminating service from this receiver
W/InputMethodManagerService( 2408): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2408): [BT Setting State] State =13
W/ContextImpl( 3989): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/PbapServerProfile( 2828): Bluetooth service disconnected
D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
I/SamsungIME( 3034): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,E/bt-btif ( 3989): bta_jv_rfcomm_stop_server
,I/jxcore-log( 6742): Radios toggled
I/jxcore-log( 6742): 
,I/BtOppRfcommListener( 3989): stopping Accept Thread
E/BtOppRfcommListener( 3989): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3989): BluetoothSocket listen thread finished
,E/bt-btif ( 3989): bta_jv_rfcomm_stop_server
,I/QuickConnect[1.1][2] ( 5114): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
I/wpa_supplicant( 3959): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3959): wlan0: Setting scan request: 0 sec 0 usec
,V/BluetoothEventManager( 2828): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/GKI_LINUX( 3989): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
W/Settings( 2408): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2408): ignore requestNetworkTransitionWakelock airplane:true
,I/BluetoothAdapterState( 3989): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/wpa_supplicant( 3959): Scan requested (ret=0) - scan timeout 30 seconds
D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
,D/BluetoothAdapterState( 3989): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
E/bt-btif ( 3989): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3989): cmd socket is not created
D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,D/btif_config_util( 3989): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/ContextImpl( 2828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
D/ConnectivityService( 2408): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2408): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2408): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2408): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2408): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2408): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2408): Attempting to switch to mobile
,D/IOP_DB_BT( 3989): db_close: nbr users 0
,D/IOP_DB_BT( 3989): db_close: free database
D/ConnectivityService( 2408): Attempting to switch to BLUETOOTH_TETHER
,D/WifiP2pService( 2408): InactiveState{ what=131204 }
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-11ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/DockEventReceiver( 2828): finishStartingService: stopping service
D/WifiP2pService( 2408): P2pEnabledState{ what=131204 }
,D/BluetoothNotiBroadcastReceiver( 2828): onReceive
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
D/WifiP2pService( 2408): sending p2p connection changed broadcast: FAILED
,D/WifiDisplayController( 2408): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/WifiP2pStateTracker( 2408): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayAdapter( 2408): onP2pDisconnected
D/IpRemoteDisplayController( 2408): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2408): WfdBridgeServer is already null
,D/QuickConnect[1.1][2] ( 5114): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5114): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2408): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2408): sending p2p connection changed broadcast: DISCONNECTED
D/WifiDisplayController( 2408): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2408): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2408): disconnect
D/WifiDisplayController( 2408): updateConnection
D/WifiDisplayController( 2408): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2408): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
V/RouteController( 1915): RTNETLINK answers: No such file or directory
D/QuickConnect[1.1][2] ( 5114): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 5114): P2pHelper.cancelConnectPeer -  mTargetList clear all 
D/QuickConnect[1.1][2] ( 5114): P2pHelper.removeP2pConfirm - skip: false
W/NetworkManagementService( 2408): route cmd failed: 
W/NetworkManagementService( 2408): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '57 route del src v6 2' failed with '400 57 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2408): '
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2408): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2408): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AuthorizationBluetoothService( 2844): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
D/QuickConnect[1.1][2] ( 5114): CentralActionManager.removeHoldingIntentAll - all request done.
,D/QuickConnect[1.1][2] ( 5114): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2408): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService( 2408): P2pDisablingState
W/WifiP2pStateTracker( 2408): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
D/WifiDisplayController( 2408): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2408): onP2pDisconnected
D/IpRemoteDisplayController( 2408): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2408): WfdBridgeServer is already null
D/WifiP2pService( 2408): P2pDisablingState{ what=147458 }
D/WifiP2pService( 2408): p2p socket connection lost
D/WifiP2pService( 2408): P2pDisabledState
D/QuickConnect[1.1][2] ( 5114): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2408): P2pDisabledState{ what=139287 }
D/WifiP2pService( 2408): DefaultState{ what=139287 }
D/WifiP2pService( 2408): P2pDisabledState{ what=139376 }
D/WifiP2pService( 2408): DefaultState{ what=139376 }
E/WifiP2pService( 2408): Unhandled message { what=139376 }
D/QuickConnect[1.1][2] ( 5114): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/QuickConnect[1.1][2] ( 5114): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService( 2408): P2pDisabledState{ what=139287 }
D/WifiP2pService( 2408): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 5114): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,D/NetUtils( 2408): android_net_utils_resetConnections in env=0x77f32250 clazz=0x9de00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2408): resetConnections(wlan0, 3)
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothAdapterState( 3989): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 3989): isSecureModeOn:false
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3989): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,W/BluetoothAdapterService( 3989): Not skipping com.android.bluetooth.hfp.HeadsetService
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
D/HeadsetService( 3989): Received stop request...Stopping profile...
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3989): Not skipping com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3989): Not skipping com.android.bluetooth.hid.HidService
,D/QuickConnect[1.1][2] ( 5114): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/A2dpService( 3989): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3989): Exit Disconnected: -1
D/Avrcp   ( 3989): Unregistering previous receiver
,D/MediaFocusControl( 2408): <<< unregisterRemoteControlDisplay
W/BluetoothAdapterService( 3989): Not skipping com.android.bluetooth.hdp.HealthService
,D/FileShare-Server( 7132): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/BluetoothA2dp( 2408): Proxy object disconnected
D/BluetoothA2dp( 5114): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5114): A2dpProfile.onServiceConnected - Bluetooth service disconnected
,W/BluetoothAdapterService( 3989): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothA2dp( 4182): Proxy object disconnected
,D/HeadsetProfile( 2828): Bluetooth service disconnected
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,E/SPPClientService( 5514): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,W/BluetoothAdapterService( 3989): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/FileShare-Server( 7132): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
W/BluetoothAdapterService( 3989): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,E/SPPClientService( 5514): [e] exceptionCaught(). NET_TIMEOUT
,W/BluetoothAdapterService( 3989): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothA2dp( 2828): Proxy object disconnected
,D/A2dpProfile( 2828): Bluetooth service disconnected
,D/BluetoothAdapterState( 3989): Stopping profile services that were post enabled
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3989): Profile still running: com.broadcom.bt.service.sap.SapService
,D/HidService( 3989): Received stop request...Stopping profile...
,D/HidService( 3989): Stopping Bluetooth HidService
,D/BluetoothInputDevice( 5114): Proxy object disconnected
D/QuickConnect[1.1][2] ( 5114): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/BluetoothInputDevice( 2828): Proxy object disconnected
,D/HidProfile( 2828): Bluetooth service disconnected
,E/SPPClientService( 5514): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,W/BluetoothHeadsetServiceJni( 3989): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3989): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 3989): Received stop request...Stopping profile...
,D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3989): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 3989): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3989): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 3989): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/PanService( 3989): Received stop request...Stopping profile...
,D/BluetoothPan( 2408): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 3989): Received stop request...Stopping profile...
D/SapService( 3989): Received stop request...Stopping profile...
,D/SapService( 3989): Stopping Bluetooth SapService
,D/GKI_LINUX( 3989): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
D/BluetoothPan( 2828): BluetoothPAN Proxy object disconnected
,D/PanProfile( 2828): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3989): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMap( 2828): Proxy object disconnected
W/BluetoothHidServiceJni( 3989): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3989): Cleaning up Bluetooth GID callback object
,D/MapProfile( 2828): Bluetooth service disconnected
D/Bluetoothsap( 2828): BluetoothSAP Proxy object disconnected
,D/SapProfile( 2828): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3989): Profile still running: com.broadcom.bt.service.sap.SapService
,W/BluetoothHealthServiceJni( 3989): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3989): Cleaning up Bluetooth Health object
D/Bluetoothsap( 2828): BluetoothSAP Proxy object disconnected
,D/SapProfile( 2828): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3989): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 3989): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3989): Cleaning up Bluetooth PAN callback object
D/BtSettings.ProfileConfig( 3989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3989): Profile still running: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3989): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
E/SPPClientService( 5514): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
D/BluetoothAdapterState( 3989): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3989): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3989): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3989): updateAdapterState state is 10
D/BluetoothAdapterService( 3989): Broadcasting updateAdapterState() to 1 receivers.
,E/SPPClientService( 5514): [b] ResponseMap empty
D/BluetoothA2dp( 2408): onBluetoothStateChange: up=false
W/BluetoothSAPServiceJni( 3989): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,W/BluetoothSAPServiceJni( 3989): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothInputDevice( 2828): onBluetoothStateChange: up=false
D/BluetoothAdapterService( 3989): Autoconnection is available 
D/BluetoothAdapterService( 3989): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 3989): Entering OffState
,D/BluetoothPbap( 2828): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 4182): onBluetoothStateChange: up=false
,D/BluetoothMap( 2828): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2828): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 5114): onBluetoothStateChange: up=false
,D/Bluetoothsap( 2828): onBluetoothStateChange: up=false
,D/Bluetoothsap( 2828): Unbinding service...
D/Bluetoothsap( 2828): onBluetoothStateChange: up=false
,D/Bluetoothsap( 2828): Unbinding service...
,D/BluetoothA2dp( 5114): onBluetoothStateChange: up=false
,W/InputMethodManagerService( 2408): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2408): [BT Setting State] State =10
,I/InputMethodManagerService( 2408): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 2751): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/SamsungIME( 3034): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/QuickConnect[1.1][2] ( 5114): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,V/BluetoothEventManager( 2828): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiNative( 2408): callSECApiBoolean - ID [13]
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3959): USE_NETWORK : USE_NETWORK OFF
W/ContextImpl( 2828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-13ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-14ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/DockEventReceiver( 2828): finishStartingService: stopping service
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
E/WifiStateMachine( 2408): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2408): Error! unhandled message{ when=-10ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothNotiBroadcastReceiver( 2828): onReceive
,D/AuthorizationBluetoothService( 2844): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2408): interfaceLinkStateChanged p2p0, true
,I/wpa_supplicant( 3959): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 2408): interfaceStatusChanged p2p0, true
,I/knox    ( 5055): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/Tethering( 2408): interfaceLinkStateChanged p2p0, false
,D/Tethering( 2408): interfaceStatusChanged p2p0, false
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/BluetoothTethering( 2408): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2408): attempted to stop reverse tether with nothing tethered
V/NetworkStats( 2408): updateIfacesLocked()
V/NetworkStats( 2408): performPollLocked(flags=0x1)
,W/ContextImpl( 5055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,V/NetworkStats( 2408): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/wpa_supplicant( 3959): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/knox    ( 5055): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/wpa_supplicant( 3959): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/knox    ( 5055): KNOXAgentService : onCreate()
,D/knox    ( 5055): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5055): KNOXAgentService. startJobThread() start
,D/knox    ( 5055): KNOXAgentService. JobThread()
D/knox    ( 5055): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5055): KNOXAgentService. startJobThread() wait
,D/knox    ( 5055): KNOXAgentService : onDestroy().
,D/knox    ( 5055): ModuleBase.cancelAllAlarmManageModule()
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 39ms
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, false
,D/Tethering( 2408): interfaceStatusChanged wlan0, false
,D/Tethering( 2408): InitialState.processMessage what=4
E/Tethering( 2408): No numeric data
,I/wpa_supplicant( 3959): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 2408): sendTetherStateChangedBroadcast 0, 0, 0
I/ConnectivityService( 2408): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 21ms
,D/WifiStateMachine( 2408): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/Settings( 5365): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 2733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 5055): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 5055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 5055): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 5055): KNOXAgentService : onCreate()
,D/knox    ( 5055): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5055): KNOXAgentService. startJobThread() start
,D/knox    ( 5055): KNOXAgentService. JobThread()
D/knox    ( 5055): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5055): KNOXAgentService. startJobThread() wait
D/knox    ( 5055): KNOXAgentService : onDestroy().
,D/knox    ( 5055): ModuleBase.cancelAllAlarmManageModule()
,D/Tethering( 2408): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2408): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2408): updateDataUsageMap
,D/CaptivePortalTracker( 2408): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2408): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4726): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): noConnectivity : true
,D/WifiStateMachine( 2408): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 5720): GC_CONCURRENT freed 2515K, 26% free 10136K/13552K, paused 9ms+4ms, total 79ms
,D/dalvikvm( 5720): WAIT_FOR_CONCURRENT_GC blocked 57ms
,I/KLMS-2.3.201 : ( 6914): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 6914): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681520165
,I/KLMS-2.3.201 : ( 6914): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 6930): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 6930): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5780): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5780): [BDLM] already registered in spp
I/SA      ( 5780): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5780): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5780): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5780): [OR] == isSIMCardReady false ==
I/SA      ( 5780): [SCU] == networkStateCheck == false
,I/SA      ( 5780): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6942): Other Intent
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 6955): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5843): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5843): getCountryCode(): countryCode = PL
,D/Headlines( 5843): Breath.onCreate
,D/Headlines( 5843): Breath timer started. interval : 30000
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5843): queryCategory.  mRequest is not initialized.
,V/AlarmManager( 2408): waitForAlarm result :8
D/HeadlinesCardManager( 5843): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5843): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5843): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5911): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 5911): SYNC; picasa accounts
,D/QuickConnect[1.1][2] ( 5114): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5114): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5114): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42268900
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,I/iu.UploadsManager( 5911): num queued entries: 0
,I/iu.UploadsManager( 5911): num updated entries: 0
,I/iu.SyncManager( 5911): NEXT; no task
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,I/Babel   ( 5365): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3157): num queued entries: 0
,I/iu.UploadsManager( 3157): num updated entries: 0
,I/iu.SyncManager( 3157): NEXT; no task
,E/SPPClientService( 5514): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5514): [SystemStateMoniter] Current Time : 413556
,E/SPPClientService( 5514): [SystemStateMoniter] No Connect : true
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 193 latestRequest time : 1449681520295 current time : 1449681520488
,E/SPPClientService( 5514): [[SystemStateMonitorService]] No Active Internet
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5514): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection...
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{452325a0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 14
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 38605 latestRequest time : 1449681520295 current time : 1449681558900
,I/EventLogService( 3157): Aggregate from 1449679758781 (log), 1449679758781 (data)
,D/dalvikvm( 3157): GC_CONCURRENT freed 2210K, 20% free 12682K/15796K, paused 6ms+9ms, total 106ms
,I/PowerManagerService( 2408): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2408): !@Sync 15
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 60027 latestRequest time : 1449681520295 current time : 1449681580322
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2578): GC_CONCURRENT freed 15711K, 33% free 33879K/50492K, paused 9ms+10ms, total 138ms
,E/Watchdog( 2408): !@Sync 16
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 90033 latestRequest time : 1449681520295 current time : 1449681610328
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2408): [PWL] Off : 455s ago
,E/Watchdog( 2408): !@Sync 17
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5843): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5843): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5843): Breath 120031 latestRequest time : 1449681520295 current time : 1449681640326
,D/Headlines( 5843): stop 
,D/Headlines( 5843): Breath.onDestroy : 
I/ActivityManager( 2408): Killing 6567:com.android.musicfx/u0a24 (adj 15): empty #43
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 18
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2408): !@Sync 19
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 525s ago
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 9203
,E/Watchdog( 2408): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2408): !@Sync 21
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,D/LightsService( 2408): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService( 2408): [PWL] Off : 600s ago
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/GAV2    ( 5603): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5603): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 22
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 3967K, 71% free 25479K/87364K, paused 17ms+19ms, total 230ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 23
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 24
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 25
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4059): GC_CONCURRENT freed 2887K, 29% free 9733K/13524K, paused 21ms+2ms, total 89ms
,E/Watchdog( 2408): !@Sync 26
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 27
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 28
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 29
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 31
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 32
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 33
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 34
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 35
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 36
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,E/SPPClientService( 5514): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2408):  next == MAX_VALUE
,E/SPPClientService( 5514): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2408): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{444729f8 u0 com.sec.spp.push/.PushClientService}
,E/Watchdog( 2408): !@Sync 37
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2408): GC_CONCURRENT freed 4161K, 72% free 25277K/87364K, paused 13ms+18ms, total 255ms
,E/Watchdog( 2408): !@Sync 38
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 39
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 41
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,D/LightsService( 2408): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11146
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11151
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11156
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11160
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11162
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11165
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11168
,E/Watchdog( 2408): !@Sync 42
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 43
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/PowerManagerService( 2408): [PWL] Off : 1265s ago
,E/Watchdog( 2408): !@Sync 44
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 45
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 46
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 47
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 48
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 49
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 4059): GC_CONCURRENT freed 2045K, 29% free 9732K/13524K, paused 4ms+4ms, total 33ms
,E/Watchdog( 2408): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 51
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 52
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 53
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 3828K, 72% free 25292K/87364K, paused 22ms+18ms, total 252ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 54
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 55
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/PowerManagerService( 2408): [PWL] Off : 1625s ago
,E/Watchdog( 2408): !@Sync 56
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 57
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/dalvikvm( 2777): GC_CONCURRENT freed 7390K, 35% free 18958K/28988K, paused 11ms+6ms, total 89ms
,E/Watchdog( 2408): !@Sync 58
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 59
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/ProcessStatsService( 2408): Prepared write state in 62ms
,I/ProcessStatsService( 2408): Prepared write state in 32ms
,I/ProcessStatsService( 2408): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-35-37.bin
,E/Watchdog( 2408): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1755s ago
,V/AlarmManager( 2408): waitForAlarm result :8
,E/SPPClientService( 5514): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 61
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 62
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 63
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 64
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,I/PowerManagerService( 2408): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 65
,TIME-OUT KILL (timeout was 1800000ms)
```
