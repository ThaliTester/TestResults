#### Test 50650278e3ff7c2_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/SSRMv2:SIOP( 2420): SIOP:: AP = 360, Delta = 10
--------- beginning of /dev/log/main
I/SELinux ( 6720): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6720):  
I/ActivityManager( 2420): Killing 5315:com.android.email/u0a157 (adj 15): empty #43
I/SELinux ( 6720): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6720):  
I/SELinux ( 6720):  
I/SELinux ( 6720): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6720): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6720): >>>>> Normal User
E/dalvikvm( 6720): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6720): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6720): in addTimaSignatureService
D/TimaKeyStoreProvider( 6720): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6720): Added TimaKesytore provider
D/dalvikvm( 6700): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42287588, skipping init
D/dalvikvm( 6720): GC_CONCURRENT freed 2994K, 31% free 9574K/13832K, paused 3ms+2ms, total 25ms
D/dalvikvm( 6720): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/SecureStorage( 6700): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1966): [INFO]: SPID(0x00000006)Credentials: uid 1000, gid 1000, pid 6700
I/SecureStorage( 1966): [INFO]: SPID(0x00000006)Received function mask & code: 00000106
D/ActivityThread( 6720): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6720): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ActivityManager( 2420): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6720): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SA      ( 5894): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5894): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5894): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5785): loadAuthorityPref(): sEnableAuthority = true
I/Icing.InternalIcingCorporaProvider( 6512): Updating corpora: A: com.test.thalitest, C: MAYBE
W/ContextImpl( 6460): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 6745): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6745):  
,I/SELinux ( 6745): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6745):  
I/SELinux ( 6745):  
I/SELinux ( 6745): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6745): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6745): >>>>> Normal User
E/dalvikvm( 6745): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9501K/10808K, paused 2ms+3ms, total 32ms
E/SELinux ( 6745): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 2ms+3ms, total 23ms
D/TimaKeyStoreProvider( 6745): in addTimaSignatureService
D/TimaKeyStoreProvider( 6745): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6745): Added TimaKesytore provider
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 2ms+3ms, total 25ms
D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
D/dalvikvm( 6745): GC_CONCURRENT freed 2998K, 31% free 9571K/13828K, paused 25ms+3ms, total 78ms
D/dalvikvm( 6745): WAIT_FOR_CONCURRENT_GC blocked 49ms
D/CapabilityManagerService New( 6745): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 6761): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6761):  
I/ActivityManager( 2420): Killing 5407:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
I/SELinux ( 6761): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6761):  
I/SELinux ( 6761):  
I/SELinux ( 6761): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6761): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6761): >>>>> Normal User
E/dalvikvm( 6761): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6761): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6761): in addTimaSignatureService
D/TimaKeyStoreProvider( 6761): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6761): Added TimaKesytore provider
D/AndroidRuntime( 6758): 
D/AndroidRuntime( 6758): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6758): CheckJNI is OFF
D/AndroidRuntime( 6758): setted country_code = Poland
D/AndroidRuntime( 6758): setted countryiso_code = PL
D/AndroidRuntime( 6758): setted sales_code = PLS
D/AndroidRuntime( 6758): readGMSProperty: start
D/AndroidRuntime( 6758): readGMSProperty: already setted!!
D/AndroidRuntime( 6758): readGMSProperty: end
D/AndroidRuntime( 6758): addProductProperty: start
D/dalvikvm( 6761): GC_CONCURRENT freed 2990K, 31% free 9575K/13828K, paused 5ms+1ms, total 27ms
D/dalvikvm( 6761): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 6758): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6758): Added shared lib libjavacore.so 0x0
I/SecureStorage( 1966): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1966): [INFO]: SPID(0x00000006)PID: 6700, TID: 6714
D/dalvikvm( 6758): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6758): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6758): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Icing.InternalIcingCorporaProvider( 6512): UpdateCorporaTask done [took 525 ms] updated apps [took 525 ms] 
I/ActivityManager( 2420): Killing 5849:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
D/PackageIntentReceiver( 6761): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6761): Not GearManger package! 
I/SELinux ( 6781): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6781):  
I/ActivityManager( 2420): Killing 5658:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 6781): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6781):  
I/SELinux ( 6781):  
I/SELinux ( 6781): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6781): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6781): >>>>> Normal User
E/dalvikvm( 6781): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6781): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 6781): in addTimaSignatureService
D/TimaKeyStoreProvider( 6781): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6781): Added TimaKesytore provider
D/dalvikvm( 6781): GC_CONCURRENT freed 2994K, 31% free 9572K/13832K, paused 3ms+1ms, total 19ms
D/dalvikvm( 6781): WAIT_FOR_CONCURRENT_GC blocked 4ms
E/memtrack( 6758): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6758): failed to load memtrack module: -2
D/MagazineService Version( 6781): Magazine-Channel: 13
I/SecureStorage( 6700): [INFO]: SPID(0x00000000)Processing data has been completed
D/MagazineService Version( 6781): Magazine-Provider: 13
D/MagazineService Version( 6781): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 6781): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 6781): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/MagazineService::MagazineService( 6781): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/dalvikvm( 6758): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 6794): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6794):  
D/MagazineService::MagazineService( 6781): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager( 2420): Killing 6108:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 6794): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6794):  
I/SELinux ( 6794):  
I/SELinux ( 6794): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6794): >>>>> Normal User
E/dalvikvm( 6794): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 6794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6794): in addTimaSignatureService
D/AndroidRuntime( 6758): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 6794): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6794): Added TimaKesytore provider
D/dalvikvm( 6794): GC_CONCURRENT freed 2997K, 31% free 9575K/13832K, paused 4ms+2ms, total 23ms
D/dalvikvm( 6794): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 6808): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6808):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6758): Shutting down VM
D/dalvikvm( 6758): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 6808): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6808):  
I/SELinux ( 6808):  
I/SELinux ( 6808): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6808): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6808): >>>>> Normal User
E/dalvikvm( 6808): >>>>> com.test.thalitest [ userId:0 | appId:10536 ]
E/SELinux ( 6808): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6808): in addTimaSignatureService
D/TimaKeyStoreProvider( 6808): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6808): Added TimaKesytore provider
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
D/dalvikvm( 6808): GC_CONCURRENT freed 3002K, 31% free 9564K/13832K, paused 3ms+1ms, total 21ms
D/dalvikvm( 6808): WAIT_FOR_CONCURRENT_GC blocked 12ms
I/SELinux ( 6821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6821):  
I/ActivityManager( 2420): Killing 5864:com.sec.android.soagent/u0a38 (adj 15): empty #43
I/SELinux ( 6821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6821):  
I/SELinux ( 6821):  
I/SELinux ( 6821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6821): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6821): >>>>> Normal User
E/dalvikvm( 6821): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
E/SELinux ( 6821): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/WebViewChromium( 6808): Binding Chromium to the background looper Looper (main, tid 1) {4228b418}
I/chromium( 6808): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6808): Initializing chromium process, renderers=0
,D/TimaKeyStoreProvider( 6821): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6821): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6821): Added TimaKesytore provider
,W/chromium( 6808): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6808): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6808): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6808): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6808): Mali API Version : 401
,I/Mali    ( 6808): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6808): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>,
W/dalvikvm( 6808): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6808): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6808): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush,
W/dalvikvm( 6808): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6808): VFY: replacing opcode 0x6e at 0x0008,
D/dalvikvm( 6821): GC_CONCURRENT freed 2999K, 31% free 9564K/13828K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 6821): WAIT_FOR_CONCURRENT_GC blocked 12ms,
,D/StatusBarManagerService( 2420): tr p:6808,o:f
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
W/dalvikvm( 6808): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6808): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6808): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6808): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6808): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6808): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6808): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6808): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6808): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6808): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6808): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6808): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6808): CordovaWebView is running on device made by: samsung
D/KidsPlatformStub( 6821): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6849): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6849):  
I/ActivityManager( 2420): Killing 6195:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,I/SELinux ( 6849): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6849):  
I/SELinux ( 6849):  
,I/SELinux ( 6849): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6849): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6849): >>>>> Normal User
,E/dalvikvm( 6849): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6849): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6849): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6849): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6849): Added TimaKesytore provider
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2420): semi p:6808,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6808): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6808): Enabling debug mode 0
,W/AwContents( 6808): nativeOnDraw failed; clearing to background color.
,D/dalvikvm( 6849): GC_CONCURRENT freed 3003K, 31% free 9567K/13832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 6849): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 6808): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2420): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 6808): showStatusIcon on inactive InputConnection,
,I/Icing   ( 3284): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,I/SELinux ( 6873): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6873):  
I/ActivityManager( 2420): Killing 5931:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
,I/SELinux ( 6873): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6873):  
I/SELinux ( 6873):  
,I/SELinux ( 6873): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6873): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6873): >>>>> Normal User
,E/dalvikvm( 6873): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6873): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6873): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6873): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6873): Added TimaKesytore provider
,I/Icing   ( 3284): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/dalvikvm( 6873): GC_CONCURRENT freed 2989K, 31% free 9575K/13828K, paused 11ms+3ms, total 35ms
,D/dalvikvm( 6873): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/UMC:Core( 6873): onCreate(): 
,D/USER_AGENT( 6873): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/JsMessageQueue( 6808): Set native->JS mode to OnlineEventsBridgeMode
,D/[SAMSUNG SMARCART NATIVE]( 6873): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6873): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/TZ_CCM_C_GetFunctionList: ( 6873): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6873): FINISHED: initialize rv:0
,D/dalvikvm( 6808): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422837c8
,D/dalvikvm( 6808): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422837c8
D/jxcore_app_log( 6808): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030901760
,D/JX-Cordova( 6808): jxcore cordova android initializing
,I/dalvikvm( 6808): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 6808): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6808): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 6873): GC_CONCURRENT freed 1883K, 23% free 10766K/13908K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 6873): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/UMC:SecurityUtils( 6873): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6873): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6873): New Flow
,I/        ( 2420): CCM JNI: In ccm_register_for_default_cert
I/        ( 2420): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2420): &ctx = 0x7bcf3618
D/TimaService( 2420): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2420): TIMA: in getTimaVersion
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
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2511): creating new ccm context...
I/TZ_CCM_SERVER( 2511): initializing ccm context...
I/TZ_CCM_SERVER( 2511): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2511): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2511): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2511): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2511): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2511): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2511): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2511): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2511): device_id = 0x0
I/TZ: mc_tlc_communication( 2511): tlc_open() was called
I/TZ: mc_tlc_communication( 2511): Opening MobiCore device
I/TZ: mc_tlc_communication( 2511): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2511): Opening the session
,I/TZ: mc_tlc_communication( 2511): tlc_open() succeeded
,I/TZ: client_server_communication( 2420): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2420): ctx = 0x7b81e690, comm = 0x81d92940, sendmsg = 0x81d94820, recvmsg = 0x81d99420
,I/TZ_init: ( 2420): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2420): nm 19456
E/TZ_init: ( 2420): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2420): trustlet initialization failed
,I/TZ_init: ( 2420): TZ_init_START...
,I/TZ_init: ( 2420): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2420): nm 19456
,I/TZ_init: ( 2420): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2420): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2420): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2420): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: ( 2420): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2420): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2420): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2420): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: ( 2420): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
E/Parcel  ( 2420): nm 19456
I/TZ: client_server_communication( 2420): Client_Server_Close was called
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2511): tlc_close() was called
,I/TZ: mc_tlc_communication( 2511): Closing the session
I/TZ: mc_tlc_communication( 2511): Free WSM
,I/TZ: mc_tlc_communication( 2511): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2511): tlc_close() succeeded
,I/TZ: client_server_communication( 2420): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6873): TIMA service call for password change success!!
,D/dalvikvm( 6808): GC_CONCURRENT freed 1286K, 19% free 11332K/13864K, paused 3ms+3ms, total 34ms
,D/UMC:AdminManager( 6873): init - start
,D/UMC:AdminManager( 6873): loadAdmins
,D/UMC:AdminManager( 6873): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6873): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6873): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6873): init - end
,V/UMC:AlarmHandler( 6873): Enter loadList
,D/EnterpriseDeviceManagerService( 2420): Creating context as user 0
,D/SPPApp  ( 6873): [SppMessageReceiver] onReceive
D/SPPApp  ( 6873): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6890): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6890):  
,I/ActivityManager( 2420): Killing 6215:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,I/SELinux ( 6890): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6890):  
I/SELinux ( 6890):  
,I/SELinux ( 6890): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6890): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6890): >>>>> Normal User
,E/dalvikvm( 6890): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6890): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6890): in addTimaSignatureService,
D/TimaKeyStoreProvider( 6890): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6890): Added TimaKesytore provider,
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 6890): GC_CONCURRENT freed 2993K, 31% free 9564K/13824K, paused 3ms+1ms, total 26ms,
,D/dalvikvm( 6890): WAIT_FOR_CONCURRENT_GC blocked 17ms,
,D/ApplicationPromenada( 6890): Application OnCreate start,
,D/ApplicationPromenada( 6890): Application OnCreate po on Create
,D/CrashReporter( 6890): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@4227a820
D/CrashReporter( 6890): Swaping uncaught exception handler
,D/ApplicationPromenada( 6890): Application OnCreate App Loader start
,D/ApplicationPromenada( 6890): Application OnCreate App Loader finish
,D/p2.ApplicationLoader( 6890): ############################## cached apps: 
,V/WebViewChromium( 6890): Binding Chromium to the background looper Looper (main, tid 1) {4228f1a0},
,I/chromium( 6890): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 6890): Initializing chromium process, renderers=0,
,W/chromium( 6890): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 6890): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 6890): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 6890): loaded /system/lib/egl/libGLESv2_mali.so,
,I/Mali    ( 6890): Mali API Version : 401,
,I/Mali    ( 6890): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,D/dalvikvm( 6808): GC_CONCURRENT freed 1922K, 18% free 14920K/18116K, paused 3ms+2ms, total 64ms,
,D/dalvikvm( 6808): WAIT_FOR_CONCURRENT_GC blocked 44ms,
,D/dalvikvm( 6808): WAIT_FOR_CONCURRENT_GC blocked 42ms,
,D/ApplicationPromenada( 6890): Application OnCreate Finish,
,I/ActivityManager( 2420): Killing 6228:com.sec.esdk.elm/u0a98 (adj 15): empty #43,
,D/PackageBroadcastService( 3284): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest,
D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3284): Module APK com.google.android.play.games already loaded,
,D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 3284): Module APK com.google.android.play.games already loaded,
,D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.gass from APK com.google.android.gms,
,D/AsyncTaskServiceImpl( 3284): Submit a task: k,
,D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.gass from APK com.google.android.gms,
,D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.vision from APK com.google.android.gms,
,D/k       ( 3284): Processing package: com.test.thalitest,
,D/GassUtils( 3284): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe,
,D/k       ( 3284): Found info for package com.test.thalitest in db.,
,D/Finsky  ( 3882): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest,
,D/dalvikvm( 6890): GC_CONCURRENT freed 1781K, 22% free 10810K/13852K, paused 3ms+2ms, total 30ms,
,D/dalvikvm( 6808): GC_FOR_ALLOC freed 5399K, 30% free 16215K/23076K, paused 53ms, total 53ms,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 6890): GC_CONCURRENT freed 2363K, 26% free 10422K/14052K, paused 2ms+2ms, total 41ms,
,I/PowerManagerService( 2420): [PWL] Off : 75s ago,
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1,
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3284, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=911),
,W/ResourceType( 6890): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75),
,W/PackageManager( 6890): Failure retrieving text 0x7f060000 in package com.android.keyguard,
W/PackageManager( 6890): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6890): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6890): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6890): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6890): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6890): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6890): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6890): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125),
W/PackageManager( 6890): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6890): 	at java.lang.Thread.run(Thread.java:841)
,I/Icing   ( 3284): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms,
,D/dalvikvm( 6808): GC_CONCURRENT freed 6666K, 32% free 17671K/25668K, paused 2ms+11ms, total 76ms,
,D/dalvikvm( 6808): WAIT_FOR_CONCURRENT_GC blocked 55ms,
,D/dalvikvm( 3284): GC_CONCURRENT freed 1743K, 19% free 12861K/15864K, paused 9ms+10ms, total 101ms
,D/dalvikvm( 3284): WAIT_FOR_CONCURRENT_GC blocked 38ms
,W/SQLiteConnectionPool( 3284): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 3284): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 6808): GC_FOR_ALLOC freed 1500K, 33% free 17372K/25668K, paused 67ms, total 67ms
,I/dalvikvm-heap( 6808): Grow heap (frag case) to 21.734MB for 3713210-byte allocation
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6890): GC_CONCURRENT freed 1996K, 26% free 10443K/14052K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 6808): GC_FOR_ALLOC freed 2450K, 37% free 18548K/29296K, paused 41ms, total 41ms
,W/jxcore-log( 6808): Initializing JXcore engine
,W/jxcore-log( 6808): JXcore engine is ready
,W/jxcore-log( 6808): Starting JXcore engine
,W/jxcore-log( 6808): Platform android
W/jxcore-log( 6808): 
,W/jxcore-log( 6808): Process ARCH arm
W/jxcore-log( 6808): 
,D/p2.ApplicationLoader( 6890): Process time: 2917
,D/p2.ApplicationLoader( 6890): ##############################  apps after loading: 
,D/dalvikvm( 6890): GC_CONCURRENT freed 2273K, 29% free 10094K/14052K, paused 3ms+14ms, total 42ms
,I/jxcore-log( 6808): JXcore Cordova bridge is ready!
I/jxcore-log( 6808): 
,W/jxcore-log( 6808): JXcore engine is started
,I/chromium( 6808): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5962): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5962): Breath 72221 latestRequest time : 1450100324095 current time : 1450100396316
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2736): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2736): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2736): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,I/VacuumService( 2736): Vacuum at: now=1450100396745 tag=VacuumService
,D/dalvikvm( 2420): GC_EXPLICIT freed 25150K, 75% free 25374K/99132K, paused 10ms+20ms, total 282ms
,I/System.out( 2736): Thread-123(HTTPLog):isShipBuild true
,I/System.out( 2736): Thread-123(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 6808): Toggling radios to true
I/jxcore-log( 6808): 
,D/dalvikvm( 2736): GC_CONCURRENT freed 1811K, 22% free 11694K/14840K, paused 7ms+5ms, total 70ms
,D/BluetoothAdapter( 6808): enable(): BT is already enabled..!
,I/WifiManager( 6808): packageName : com.test.thalitest
,I/WifiManager( 6808): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=6808, uid=10536
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=6808, uid=10536 requires android.permission.INTERACT_ACROSS_USERS,
W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6808, uid=10536 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2420): disconnect: pid=6808, uid=10536
I/jxcore-log( 6808): Radios toggled
I/jxcore-log( 6808): 
I/wpa_supplicant( 3969): [wpa_supplicant_ctrl_iface_process] : DISCONNECT,
I/jxcore-log( 6808): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 6808): 
I/wpa_supplicant( 3969): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/jxcore-log( 6808): Perf Test app loaded loaded
I/jxcore-log( 6808): 
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/jxcore-log( 6808): check test folder
I/jxcore-log( 6808): 
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/jxcore-log( 6808): found test : ./testFindPeers.js
I/jxcore-log( 6808): 
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3969): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3969): First Scan Start
I/wpa_supplicant( 3969): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true,
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
I/wpa_supplicant( 3969): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3969): Skip scan - already scanning
,I/jxcore-log( 6808): found test : ./testSendData.js
I/jxcore-log( 6808): 
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 6942): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6942):  
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
D/ConnectivityService( 2420): Attempting to switch to mobile
,D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
E/WifiStateMachine( 2420): Error! unhandled message{ when=-42ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-41ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6942): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6942):  
I/SELinux ( 6942):  
,I/SELinux ( 6942): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6942): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6942): >>>>> Normal User
,E/dalvikvm( 6942): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6942): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/TimaKeyStoreProvider( 6942): in addTimaSignatureService
,W/NetworkManagementService( 2420): route cmd failed: 
W/NetworkManagementService( 2420): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 6942): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6942): Added TimaKesytore provider
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x7bbc2298 clazz=0x62300001 iface=wlan0 mask=0x3
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,V/NativeCrypto( 2846): Read error: ssl=0x7b9b68b8: I/O error during system call, Connection timed out
,E/SPPClientService( 5622): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5622): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5622): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5622): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5622): [b] ResponseMap empty
,V/NativeCrypto( 2846): SSL shutdown failed: ssl=0x7b9b68b8: I/O error during system call, Broken pipe
,D/dalvikvm( 6942): GC_CONCURRENT freed 2990K, 31% free 9578K/13828K, paused 3ms+2ms, total 63ms
,D/dalvikvm( 6942): WAIT_FOR_CONCURRENT_GC blocked 37ms
,I/chromium( 6808): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/PhenotypeConfigurator( 2736): IOException while sending for: 
W/PhenotypeConfigurator( 2736): java.net.ConnectException: failed to connect to example.com/93.184.216.34 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
W/PhenotypeConfigurator( 2736): 	at libcore.io.IoBridge.connect(IoBridge.java:114)
W/PhenotypeConfigurator( 2736): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:192)
W/PhenotypeConfigurator( 2736): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:459)
W/PhenotypeConfigurator( 2736): 	at java.net.Socket.connect(Socket.java:843)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:131)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.Connection.connect(Connection.java:949)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:411)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpEngine.sendSocketRequest(HttpEngine.java:343)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:289)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:345)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:89)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:197)
W/PhenotypeConfigurator( 2736): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:254)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:948)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:766)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:674)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:658)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:1353)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:799)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:753)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.c(SourceFile:475)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator.a(SourceFile:438)
W/PhenotypeConfigurator( 2736): 	at com.google.android.gms.gcm.au.run(SourceFile:140)
W/PhenotypeConfigurator( 2736): Caused by: libcore.io.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
W/PhenotypeConfigurator( 2736): 	at libcore.io.Posix.connect(Native Method)
W/PhenotypeConfigurator( 2736): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:85)
W/PhenotypeConfigurator( 2736): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:144)
W/PhenotypeConfigurator( 2736): 	at libcore.io.IoBridge.connect(IoBridge.java:112)
W/PhenotypeConfigurator( 2736): 	... 22 more
,D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
V/NetworkStats( 2420): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/System.out( 6942): Inside WakeupProvider
,I/System.out( 6942): Inside onCreate() of WakeupTriggerProvide
V/NetworkStats( 2420): performPollLocked() took 25ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/VlingoApplication( 6942): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6942): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6942): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 4762): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4762): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4762): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4762): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2420): Killing 5394:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
D/DialogFlow( 6942): initQueue()
,D/NearbySettings( 4762): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4762): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4762): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4762): MountReceiver.mPrefHandler - 7002
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 370, Delta = 10
,I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6671): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6671): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6671): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6671): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4787): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6671): noConnectivity : true
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 6973): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6973):  
,I/SELinux ( 6973): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6973):  
I/SELinux ( 6973):  
,I/SELinux ( 6973): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6973): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6973): >>>>> Normal User
,E/dalvikvm( 6973): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6973): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6973): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6973): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6973): Added TimaKesytore provider
,I/wpa_supplicant( 3969): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3969): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3969): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/dalvikvm( 6973): GC_CONCURRENT freed 3001K, 31% free 9565K/13828K, paused 6ms+2ms, total 35ms
D/dalvikvm( 6973): WAIT_FOR_CONCURRENT_GC blocked 28ms
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 3969): Associated with C0.AA.48
I/wpa_supplicant( 3969): freq(2412) increment count 2
I/wpa_supplicant( 3969): meet head of list.
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
I/ActivityManager( 2420): Killing 6256:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3969): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3969): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3969): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/WifiNative( 2420): callSECApiVoid - ID [50]
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
I/SELinux ( 6987): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6987):  
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9501K/10808K, paused 3ms+4ms, total 36ms
I/SELinux ( 6987): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6987):  
I/SELinux ( 6987):  
I/SELinux ( 6987): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6987): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6987): >>>>> Normal User
E/dalvikvm( 6987): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
E/SELinux ( 6987): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 3ms+4ms, total 30ms
D/TimaKeyStoreProvider( 6987): in addTimaSignatureService
D/TimaKeyStoreProvider( 6987): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6987): Added TimaKesytore provider
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 2ms+4ms, total 29ms
D/dalvikvm( 6987): GC_CONCURRENT freed 2998K, 31% free 9570K/13832K, paused 2ms+1ms, total 21ms
D/dalvikvm( 6987): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
I/ActivityManager( 2420): Killing 6342:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
I/SELinux ( 7006): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7006):  
I/dhcpcd  ( 6999): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6999): bssid match
I/SELinux ( 7006): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7006):  
I/SELinux ( 7006):  
I/SELinux ( 7006): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7006): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7006): >>>>> Normal User
E/dalvikvm( 7006): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7006): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7006): in addTimaSignatureService
D/TimaKeyStoreProvider( 7006): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7006): Added TimaKesytore provider
D/dalvikvm( 7006): GC_CONCURRENT freed 2997K, 31% free 9567K/13828K, paused 3ms+2ms, total 30ms
D/dalvikvm( 7006): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/KLMS-2.3.201 : ( 7006): KLMSValidator() : checkQATesting()
I/KLMS-2.3.201 : ( 7006): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450100399116
I/KLMS-2.3.201 : ( 7006): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
I/ActivityManager( 2420): Killing 6392:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
I/SELinux ( 7018): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7018):  
D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
I/SELinux ( 7018): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7018):  
I/SELinux ( 7018):  
I/SELinux ( 7018): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7018): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7018): >>>>> Normal User
E/dalvikvm( 7018): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
E/SELinux ( 7018): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 7018): in addTimaSignatureService
D/TimaKeyStoreProvider( 7018): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7018): Added TimaKesytore provider
D/dalvikvm( 7018): GC_CONCURRENT freed 2994K, 31% free 9574K/13832K, paused 4ms+2ms, total 23ms
D/dalvikvm( 7018): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/SO_AGENT( 7018): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 7018): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
I/SA      ( 5894): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5894): [BDLM] already registered in spp
I/SA      ( 5894): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5894): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5894): [OR] == isSIMCardReady false ==
I/SA      ( 5894): [SCU] == networkStateCheck == false
,I/SA      ( 5894): [OR] onReceive END
I/ActivityManager( 2420): Killing 6416:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7030): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7030):  
,I/SELinux ( 7030): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7030):  
I/SELinux ( 7030):  
,I/SELinux ( 7030): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7030): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7030): >>>>> Normal User
,E/dalvikvm( 7030): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7030): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7030): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7030): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7030): Added TimaKesytore provider
,D/dalvikvm( 7030): GC_CONCURRENT freed 3008K, 31% free 9558K/13832K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7030): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/sCloudBackupApp( 7030): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7030): Other Intent
I/ActivityManager( 2420): Killing 6430:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7043): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7043):  
,I/SELinux ( 7043): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7043):  
I/SELinux ( 7043):  
,I/SELinux ( 7043): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7043): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7043): >>>>> Normal User
,E/dalvikvm( 7043): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7043): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7043): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7043): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7043): Added TimaKesytore provider
,D/dalvikvm( 7043): GC_CONCURRENT freed 3012K, 31% free 9551K/13828K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7043): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7043): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7043): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7043): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7043): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 5678:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5962): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5962): getCountryCode(): countryCode = PL
,D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5962): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5962): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5962): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5962): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5962): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5962): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7056): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7056):  
,I/SELinux ( 7056): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7056):  
I/SELinux ( 7056):  
,I/SELinux ( 7056): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7056): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7056): >>>>> Normal User
,E/dalvikvm( 7056): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7056): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7056): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7056): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7056): Added TimaKesytore provider
,D/dalvikvm( 7056): GC_CONCURRENT freed 2999K, 31% free 9570K/13832K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 7056): WAIT_FOR_CONCURRENT_GC blocked 19ms
V/AlarmManager( 2420): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
,V/WebViewChromium( 7056): Binding Chromium to the background looper Looper (main, tid 1) {4228c158}
,I/chromium( 7056): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7056): Initializing chromium process, renderers=0
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/chromium( 7056): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7056): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7056): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7056): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7056): Mali API Version : 401
,I/Mali    ( 7056): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7056): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7056): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService( 2420): InactiveState{ what=143375 },
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 },
,D/WifiStateMachine( 2420): VerifyingLinkState enter,
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check,
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter,
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling,
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE,
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling,
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults,
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info ,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/NSApplication( 7056): Starting up...
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2420): updateIfacesLocked()
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit,
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked() took 21ms
,I/iu.Environment( 6027): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 2420): Killing 6278:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/QuickConnect[1.1][2] ( 5219): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5219): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
,I/SELinux ( 7130): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7130):  
,I/SELinux ( 7130): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7130):  
I/SELinux ( 7130):  
,I/SELinux ( 7130): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7130): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7130): >>>>> Normal User
,E/dalvikvm( 7130): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7130): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7130): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7130): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7130): Added TimaKesytore provider
,D/dalvikvm( 7130): GC_CONCURRENT freed 2985K, 31% free 9579K/13828K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 7130): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7149): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7149):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/ActivityManager( 2420): Killing 4936:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,D/PackageManager( 2420): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@42e30cb0, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/SELinux ( 7149): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7149):  
I/SELinux ( 7149):  
,I/SELinux ( 7149): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7149): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7149): >>>>> Normal User
,E/dalvikvm( 7149): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7149): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7149): in addTimaSignatureService
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7149): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7149): Added TimaKesytore provider
,I/SELinux ( 7162): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7162):  
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7162): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7162):  
I/SELinux ( 7162):  
,I/SELinux ( 7162): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7162): >>>>> Normal User
,E/dalvikvm( 7162): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager( 2420): Killing 6526:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7162): in addTimaSignatureService
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/TimaKeyStoreProvider( 7162): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7162): Added TimaKesytore provider
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "sms"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4787): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/HarmonyEASService( 2420): Updating for all 1
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "smsto"
,I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredServicesCache( 2764): empty dynamic service
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7149): GC_CONCURRENT freed 3006K, 31% free 9563K/13832K, paused 11ms+2ms, total 35ms
,D/dalvikvm( 7149): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BadgeProvider( 7149): onCreate
,D/BadgeProvider( 7149): DatabaseHelper
,D/BadgeProvider( 7149): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7162): GC_CONCURRENT freed 2993K, 31% free 9574K/13828K, paused 14ms+5ms, total 72ms
,D/dalvikvm( 7162): WAIT_FOR_CONCURRENT_GC blocked 53ms
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BadgeProvider( 7149): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7149): sendNotify, [notify] : null
D/BadgeProvider( 7149): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7149): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7149): update, [UpdateCount] : 1
,D/Launcher.Model( 2771): reloadBadges entered.
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/hcjo    ( 6048): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6048): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6048): exit::IDLE
,D/InitializeManagerStateMachine( 6048): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6048): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6048): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6048): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6048): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6048): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6048): entry::SUCCESS
,D/hcjo    ( 6048): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/SPPClientService( 5622): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5622): [SystemStateMoniter] Current Time : 154364
,E/SPPClientService( 5622): [SystemStateMoniter] No Connect : true
,D/hcjo    ( 6048): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6048): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6048): exit::SUCCESS
,D/InitializeManagerStateMachine( 6048): entry::IDLE
,E/SPPClientService( 5622): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4762): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4762): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4762): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5622): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5622): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4762): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4762): MountReceiver.onReceive - Keep current state
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5622): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5622): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 4762): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4762): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4762): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4762): MountReceiver.onReceive - Keep current state
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2420): Killing 6376:com.sec.phone/1001 (adj 15): empty #43
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5622): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,D/NearbySettings( 4762): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4762): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5622): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5622): [g] getNetMCC return empty string
,I/Icing.InternalIcingCorporaProvider( 6512): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,I/SELinux ( 7183): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7183):  
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7183): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7183):  
I/SELinux ( 7183):  
,I/SELinux ( 7183): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7183): >>>>> Normal User
,E/dalvikvm( 7183): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
,E/SELinux ( 7183): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7183): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7183): Cannot add TimaSignature Service, License check Failed
,I/Icing.InternalIcingCorporaProvider( 6512): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] 
,D/ActivityThread( 7183): Added TimaKesytore provider
,D/dalvikvm( 7183): GC_CONCURRENT freed 2996K, 31% free 9564K/13824K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7183): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/FileShare-Server( 7183): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/SELinux ( 7195): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7195):  
,W/ApplicationsProvider( 2964): Could not fetch usage stats
W/ApplicationsProvider( 2964): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2964): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2964): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2964): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2964): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2964): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7195): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7195):  
I/SELinux ( 7195):  
,I/SELinux ( 7195): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7195): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7195): >>>>> Normal User
,E/dalvikvm( 7195): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 7195): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7195): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7195): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7195): Added TimaKesytore provider,
,D/dalvikvm( 7195): GC_CONCURRENT freed 2999K, 31% free 9571K/13832K, paused 4ms+2ms, total 31ms,
,D/dalvikvm( 7195): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/BezelQuickConnect( 5231): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED,
,D/BezelQuickConnect( 5231): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms,
,I/ActivityManager( 2420): Killing 6447:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43,
,I/jxcore-log( 6808): BLE advertisement not supported: Build version is 19,
I/jxcore-log( 6808): 
,D/PackageBroadcastService( 3284): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms,
,D/dalvikvm( 2420): GC_EXPLICIT freed 3585K, 75% free 25448K/99132K, paused 10ms+25ms, total 264ms,
,I/PCWCLIENTTRACE_PushUtil( 6671): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6671): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6671): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6671): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
,D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0,
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info ,
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions,
,I/KLMS-2.3.201 : ( 7006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout,
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...,
,I/KLMS-2.3.201 : ( 7006): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450100402924,
,I/KLMS-2.3.201 : ( 7006): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7018): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
,I/LocationTagReadyService( 3468): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true,
D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true,
,I/SO_AGENT( 7018): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3596): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query,
,I/SELinux ( 7221): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7221):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9501K/10808K, paused 4ms+5ms, total 50ms,
,I/SELinux ( 7221): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7221):  
I/SELinux ( 7221):  
,I/SELinux ( 7221): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7221): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7221): >>>>> Normal User
,E/dalvikvm( 7221): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7221): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 4ms+4ms, total 38ms
,D/TimaKeyStoreProvider( 7221): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7221): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7221): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 3ms+4ms, total 34ms
,I/SELinux ( 7233): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7233):  
,I/SA      ( 5894): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5894): [BDLM] already registered in spp
,I/SA      ( 5894): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5894): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5894): [OR] == isSIMCardReady false ==
,I/SA      ( 5894): [SCU] == networkStateCheck == true
,I/SA      ( 5894): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5894): isChinaCountryCode : false
,I/SA      ( 5894): [OR] == networkStateCheck true ==
,I/SA      ( 5894): [OR] GetMyCountryZoneTask
,I/SA      ( 5894): [OR] onReceive END
I/SELinux ( 7233): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7233):  
I/SELinux ( 7233):  
,I/SELinux ( 7233): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7233): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7233): >>>>> Normal User
,E/dalvikvm( 7233): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7233): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5894): [SRS] prepareGetMyCountryZone
,I/SA      ( 5894): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5894): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7030): Other Intent
,I/System.out( 6987): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/TimaKeyStoreProvider( 7233): in addTimaSignatureService
D/dalvikvm( 7221): GC_CONCURRENT freed 2998K, 31% free 9571K/13832K, paused 5ms+1ms, total 46ms
,D/dalvikvm( 7221): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/TimaKeyStoreProvider( 7233): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7233): Added TimaKesytore provider
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7043): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/SA      ( 5894): [TPMU] GetMccFromDB : null
I/SA      ( 5894): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5894): [TPM] isNoProxy(default) : true
,I/SA      ( 5894): [RC New] Execute method=[GET] start
,I/System.out( 6987): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 6987): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Headlines( 5962): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5962): getCountryCode(): countryCode = PL
,D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5962): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5962): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5962): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5962): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5962): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5962): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 6027): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5219): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5219): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
D/dalvikvm( 7233): GC_CONCURRENT freed 2996K, 31% free 9565K/13824K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7233): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,V/KVNProvider( 7233): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7233): getFindoCursor query string : 
,D/hcjo    ( 6048): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6048): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6048): exit::IDLE
,D/InitializeManagerStateMachine( 6048): entry::NETWORK_CHECK
,V/KVNProvider( 7233): getTagSearchCursor() tagSearchCursor count : 0
D/InitializeManagerStateMachine( 6048): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6048): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6048): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6048): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6048): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6048): entry::SUCCESS
,D/hcjo    ( 6048): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6048): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6048): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6048): exit::SUCCESS
,D/InitializeManagerStateMachine( 6048): entry::IDLE
,I/System.out( 6987): AsyncTask #1 calls detatch()
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ActivityManager( 2420): Killing 6075:com.android.calendar/u0a144 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/System.err( 6987): com.sec.android.fota.osp.http.RestClientException
W/System.err( 6987): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6987): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6987): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6987): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 6987): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6987): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 6987): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6987): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6987): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 6987): Caused by: java.lang.NullPointerException
W/System.err( 6987): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 6987): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 6987): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6987): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6987): 	... 8 more
,E/SPPClientService( 5622): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5622): [SystemStateMoniter] Current Time : 156394
,E/SPPClientService( 5622): [SystemStateMoniter] No Connect : false
,I/ActivityManager( 2420): Killing 6243:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 5622): GC_CONCURRENT freed 1974K, 25% free 10434K/13812K, paused 3ms+3ms, total 35ms
,I/Icing   ( 3284): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3284): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 5894): [RC New] [v2liruge] api execute + 705
,I/SA      ( 5894): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5894): AsyncTask #2 calls detatch()
,I/SA      ( 5894): [TPMU] getNetworkMcc : 
,I/SA      ( 5894): [SCU] saveMccToPreferece Start
,I/SA      ( 5894): [SCU] RegionMCC : 260
,I/SA      ( 5894): [SSP] query invoked
,I/SA      ( 5894): [TPMU] GetMccFromDB : null
,I/SA      ( 5894): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5894): [SCU] saveMccToPreferece End
,I/SA      ( 5894): [RC New] executeRequest [v2liruge] end. 740
I/SA      ( 5894): [RC New] Execute end
I/SA      ( 5894): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5894): [OR] GetMyCountryZoneTask Success
,E/SPPClientService( 5622): [b] __InitReply__
,I/ActivityManager( 2420): Killing 6293:com.google.android.music:main/u0a125 (adj 15): empty #43,
I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11),
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 158096,
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0),
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3511),
,I/GAV2    ( 7056): Thread[GAThread,5,main]: No campaign data found.,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Finsky  ( 3882): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 3882): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6671): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6671): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6671): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6671): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6671): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6671): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6671): sales region : global,
I/PCWCLIENTTRACE_PushUtil( 6671): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6671): [ensureRegistration] - No Samsung account,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 350, Delta = -20,
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4,
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 7288,
,D/PreloadUpdateManagerStateMachine( 6048): execute::IDLE:EXECUTE,
,D/PreloadUpdateManagerStateMachine( 6048): exit::IDLE,
,D/PreloadUpdateManagerStateMachine( 6048): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6048): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6048): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6048): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6048): entry::IDLE,
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null,
D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/PreloadUpdateManagerStateMachine( 6048): execute::IDLE:EXECUTE,
,D/PreloadUpdateManagerStateMachine( 6048): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6048): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6048): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6048): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6048): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6048): entry::IDLE,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5962): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5962): Breath 10769 latestRequest time : 1450100403342 current time : 1450100414111
,E/Watchdog( 2420): !@Sync 5,
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{447a8fa0 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 340, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 105s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 7412,
,D/BatteryService( 2420): level:100, scale:100, status:3, health:9, present:true, voltage: 4390, temperature: 300, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UsbDeviceManager( 2420): handleMessage -> MSG_POWER_STATE = 0
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/lights  ( 2420): button : 1 +
D/lights  ( 2420): button : 1 -
,D/lights  ( 2420): led_pattern : 0 +
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/BatteryService( 2420): turn off LED
D/PowerManagerService( 2420): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2420): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2420): Waking up from sleep...
D/PowerManagerService( 2420): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2420): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2420): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2420): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2420): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/lights  ( 2420): led_pattern : 0 -
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2420): HAL: batch Dry Run is complete
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/PowerManagerService( 2420): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 4ms
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2420): [DAB] no lux value from sensor manager,
D/DisplayPowerController( 2420): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
D/UsbDeviceManager( 2420): sending intent : ACTION_USB_CABLE_STATE : connected = false
I/libsuspend( 2420): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2420): !@[s] autosuspend_autosleep_disable done
,D/NotificationService( 2420): cancelNotificationLocked
D/SurfaceFlinger( 1922): Screen acquired, type=0 flinger=0x41ef1550
D/PowerManagerService( 2420): unblankAllDisplays() is called.
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/PowerManagerService( 2420): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(3) - 5
D/NotificationService( 2420):  hasClearableItems
I/Sensors ( 2420): HAL:resetDataRates mEnabled=4
D/NotificationService( 2420):  has clearable items no 
D/NotificationService( 2420): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2420): cancelNotificationLocked: cancel alarm
D/PowerManagerService( 2420): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 186695
D/RampAnimator( 2420): Light Animator Finished currentValue=8
,D/SensorManager( 2420): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 65558
D/SensorService( 2420): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2420): AutoRotationSensor::activate (ident=0x7b85e300, enabled=1)
D/SensorService( 2420): AutoRotationSensor::AR_init
,I/Sensors ( 2420): HAL: batch Dry Run is complete
D/PowerManagerService( 2420): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 23ms
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/Sensors ( 2420): HAL:resetDataRates mEnabled=4
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/UsbDeviceManager( 2420): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/SensorManager( 2420): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/KeyguardServiceDelegate( 2420): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@436935e0)
,D/KeyguardViewMediator( 2582): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 2582): notifyScreenOnLocked
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
D/KeyguardViewMediator( 2582): handleNotifyScreenOn
,D/KeyguardViewManager( 2582): onScreenTurnedOn()
,V/KeyguardViewManager( 2582): send wm null token: host was null
V/KeyguardServiceDelegate( 2420): **** SHOWN CALLED ****
I/KeyguardEffectViewMain( 2582): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2582): KeyguardEffectViewParticleSpace : screenTurnedOn
I/SELinux ( 7422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7422):  
D/InputDispatcher( 2420): setInputDispatchMode: enabled=1, frozen=0
D/LockPatternUtils( 2582): isPcwEnable = 10
I/WindowManager( 2420): No lock screen! windowToken=null
D/VisualEffectParticleEffect( 2582): screenOnAnimationStart
D/PowerManagerNotifier( 2420): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2420): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2420): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2420): !@ElectronBeam exit
I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1922): id=14 Removed FlectronBea (-2/10)
,D/lights  ( 2420): lcd : 8 +
,D/PowerManagerService( 2420): Excessive delay in ElectronBeam exit: 12ms
,D/lights  ( 2420): lcd : 8 -
D/DisplayPowerController( 2420): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2420): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/BatteryMeterView( 2582): onDraw batteryColor : -1
,I/SELinux ( 7422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7422):  
I/SELinux ( 7422):  
,I/SELinux ( 7422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7422): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7422): >>>>> Normal User
,E/dalvikvm( 7422): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 7422): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SensorService( 2420): AutoRotationSensor::process: Acc  eventTimestamp = 186782226425, previousAccTimestamp = 70369054183, difference = 116413172242 
,D/SensorService( 2420): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 7422): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7422): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7422): Added TimaKesytore provider
,D/DisplayPowerController( 2420): [api] [DAB] onSensorChanged : 1st lux : 5.0
,D/DisplayPowerController( 2420): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 5.0 < 15.0 (0.0)
,D/SensorService( 2420): AutoRotationSensor::process: Acc  eventTimestamp = 186848889248, previousAccTimestamp = 70369054183, difference = 116479835065 
D/SensorService( 2420):  [AR] 0.3 0.0 9.8
,D/SensorService( 2420): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2420): Excessive delay in unblankDisplay() while turning screen on: 248ms
,D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2420): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 250ms
,D/LockPatternUtils( 2582): isPcwEnable = 10
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
,D/PalmMotionService( 2420): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotionService( 2420): SURFACE_PALM_SWIPE: 1
,I/chromium( 6808): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
E/MotionRecognitionService( 2420):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:TSP:AirViewOnOff( 2420): SettingsAirViewInfo:: 000000000
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.USER_PRESENT
,D/SamsungIME( 2991): showDlgMsgBox : false true true
,I/NfcService( 2764): applyRouting return - 2 
,E/NfcService( 2764): callback == null
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,I/chromium( 6808): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/STATUSBAR-NotificationService( 2420): ACTION_SCREEN_ON
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 2420): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/libGLESv2( 6808): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6808): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SecExternalDisplayIntents_Java( 2420): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2420): Excessive delay in MISC setInteractive(true) while turning screen on: 160ms
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2420): Excessive delay in nativeSetInteractive(true): 162ms
D/PowerManagerService( 2420): SecHardwareInterface.setBatteryADC : true
,D/IpRemoteDisplayController( 2420): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2420): Bridge Server is not available
,D/PersonaManagerService( 2420): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2420): MSG_ACTION_SCREEN_ON called
,D/dalvikvm( 7422): GC_CONCURRENT freed 3000K, 31% free 9563K/13824K, paused 6ms+5ms, total 62ms
,D/dalvikvm( 7422): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/StatusBarManagerService( 2420): semi p:6808,o:f
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/KIES_RECEIVE( 7422): [APK BnR] Receive KIES_USB_DISCONNECT
,I/NfcService( 2764): NFC: Screen On & Cover Open
W/ContextImpl( 7422): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,E/libGLESv2( 6808): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6808): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
E/libGLESv2( 6808): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6808): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,I/NfcService( 2764): applyRouting return - 2 
,E/NfcService( 2764): callback == null
,D/STATUSBAR-NetworkController( 2582): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,E/TranscodeReceiver( 7221): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7221): core_num = 4
,D/dalvikvm( 7221): No JNI_OnLoad found in /system/lib/libsavsff.so 0x4228bad8, skipping init
,W/linker  ( 7221): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 7221): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 7221): dsp : 720, swkey : false, Cores : 4, Clock : 0
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,I/SELinux ( 7438): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7438):  
,I/SELinux ( 7438): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7438):  
I/SELinux ( 7438):  
,I/SELinux ( 7438): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7438): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7438): >>>>> Normal User
,E/dalvikvm( 7438): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7438): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/QuickConnect[1.1][2] ( 5219): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 5219): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5219): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
,V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
V/QuickConnect[1.1][2] ( 5219): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
D/QuickConnect[1.1][2] ( 5219): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5219): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5219): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5219): BleHelper.startScan - shouldScanBleFg = false
,D/TimaKeyStoreProvider( 7438): in addTimaSignatureService
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5419): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/TimaKeyStoreProvider( 7438): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7438): Added TimaKesytore provider
,D/PowerManagerService( 2420): [PWL] sb release: PowerManagerService.Broadcasts
,D/dalvikvm( 6512): GC_CONCURRENT freed 2525K, 28% free 10052K/13836K, paused 5ms+4ms, total 63ms
,D/dalvikvm( 7438): GC_CONCURRENT freed 2991K, 31% free 9578K/13832K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 7438): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SELinux ( 7454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7454):  
I/ActivityManager( 2420): Killing 6615:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7454):  
I/SELinux ( 7454):  
,I/SELinux ( 7454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7454): >>>>> Normal User
,E/dalvikvm( 7454): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7454): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7454): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7454): Added TimaKesytore provider
,D/dalvikvm( 7454): GC_CONCURRENT freed 2995K, 31% free 9572K/13828K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7454): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/iu.Environment( 6027): update battery state; isPlugged? false*
,D/PicasaUploader( 7454):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7454):    wifiOnlyVideo changed to true
,D/PicasaUploader( 7454):    syncOnBattery changed to true
,D/PicasaUploaderSync( 7454): sync account database
,I/iu.SyncManager( 6027): SYNC; picasa accounts
,I/ActivityManager( 2420): Killing 6532:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/iu.UploadsManager( 6027): num queued entries: 0
,I/iu.UploadsManager( 6027): num updated entries: 0
,D/PicasaUploaderSync( 7454): accounts in DB=1
,I/iu.Environment( 3284): update battery state; isPlugged? false*
,I/iu.SyncManager( 6027): NEXT; no task
D/PicasaUploaderSyncManager( 7454): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7454): background data: true
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3284): num queued entries: 0
,I/iu.UploadsManager( 3284): num updated entries: 0
,I/iu.SyncManager( 3284): NEXT; no task
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/PicasaUploaderSyncManager( 7454): battery info: false
,D/LockPatternUtils( 2582): isPcwEnable = 10
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5419): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5419): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5419): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5419): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1450121880000
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1450100435154
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5419): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5419): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5419): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5419): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5419): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5419): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SSRMv2:TSP:AirViewOnOff( 2420): SettingsAirViewInfo:: 000000000
,D/SensorService( 2420):   0.3 0.0 9.9
,D/lights  ( 2420): button : 0 +
,D/lights  ( 2420): button : 0 -
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2420): level:100, scale:100, status:2, health:2, present:true, voltage: 4355, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/PowerManagerService( 2420): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2582): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2420): [api] [s] wakeUp (uid: 10019 pid: 2582) eventTime = 196605
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/PowerUI ( 2582): playSound : 1
D/UsbDeviceManager( 2420): handleMessage -> MSG_POWER_STATE = 1
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,V/Vibrator( 2582): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2582): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
I/EntropyMixer( 2420): Writing entropy...
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
V/VibratorService( 2420): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2420): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2420): JNI vibratorOff()
D/VibratorService( 2420): JNI vibratorOn() : 100
D/PowerUI ( 2582): RINGER_MODE_VIBRATE
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely,
,D/UsbDeviceManager( 2420): sending intent : ACTION_USB_CABLE_STATE : connected = true,
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
E/TranscodeReceiver( 7221): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/BatteryMeterView( 2582): onDraw batteryColor : -1
,D/TranscodeService( 7221): onCreate()
,I/SCloudBackupReceiver( 7030): Other Intent,
,D/dalvikvm( 7221): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x4228bad8, skipping init,
D/PicasaUploaderSyncManager( 7454): battery info: true
,D/dalvikvm( 7221): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x4228bad8, skipping init,
,D/dalvikvm( 7221): No JNI_OnLoad found in /system/lib/libsthmb.so 0x4228bad8, skipping init,
,I/iu.Environment( 6027): update battery state; isPlugged? true*,
D/TranscodeService( 7221): power? : true / screen off : false
,D/TranscodeService( 7221): releaseTranscodeThread.,
,D/VibratorService( 2420): JNI vibratorOff(),
I/iu.FingerprintManager( 6027): Start processing all media
I/iu.FingerprintManager( 6027): Start processing media store URI: content://media/external/images/media
I/iu.UploadsManager( 6027): num queued entries: 0
I/iu.UploadsManager( 6027): num updated entries: 0
I/iu.SyncManager( 6027): NEXT; no task
,I/iu.Environment( 3284): update battery state; isPlugged? true*,
I/iu.UploadsManager( 3284): num queued entries: 0
,I/iu.UploadsManager( 3284): num updated entries: 0
,I/iu.SyncManager( 3284): NEXT; no task
,I/iu.FingerprintManager( 6027): Start processing media store URI: content://media/external/video/media
,E/NetworkScheduler.SchedulerReceiver( 2846): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2846): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3284): Start processing all media
,I/iu.FingerprintManager( 3284): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 6027): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 6027): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3284): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 6027): Finished generating fingerprints; 0.100 seconds
,I/iu.FingerprintManager( 6027):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3284): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3284): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3284): Finished generating fingerprints; 0.086 seconds
,I/iu.FingerprintManager( 3284):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,I/PhenotypeConfigurator( 2736): Scheduling Phenotype for one-off execution 11408 seconds from now (1450100444298)
,D/GetConfigurationSnapshotOperation( 2736): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 2420): GC_EXPLICIT freed 3022K, 75% free 25338K/99132K, paused 12ms+37ms, total 334ms
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2736): GC_CONCURRENT freed 1769K, 21% free 11886K/14984K, paused 6ms+7ms, total 69ms
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Watchdog( 2420): !@Sync 6
,D/LocationManagerService( 2420): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{42f0e8d0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 0.0 9.9
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2420): level:100, scale:100, status:2, health:2, present:true, voltage: 4381, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2420):   0.3 -0.0 9.9
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{447bfa10 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5419): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5419): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5419): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5419): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5419): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5419): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5419): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5419): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5419): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5962): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5962): Breath 58231 latestRequest time : 1450100403342 current time : 1450100461573
,I/SELinux ( 7488): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7488):  
,I/SELinux ( 7488): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7488):  
I/SELinux ( 7488):  
,I/SELinux ( 7488): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7488): >>>>> Normal User
,E/dalvikvm( 7488): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7488): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7488): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7488): Added TimaKesytore provider
,D/dalvikvm( 7488): GC_CONCURRENT freed 3006K, 31% free 9557K/13828K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7488): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SensorService( 2420):   0.3 0.0 9.9
,E/SPPClientService( 7488): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7488): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7488): PushLog.txt file is not deleted.
,D/SPPClientService( 7488): PushLog.txt file is not deleted.
,D/SPPClientService( 7488): ============PushLog. stop!
,E/SPPClientService( 5622): [b] __PingReply__
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(1) - 5
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/NotificationService( 2420): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,D/RCPManagerService( 2420): NotificationReceiver onReceive()
D/RCPManagerService( 2420):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2420): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298420
D/RCPManagerService( 2420): getPolicy: policy value returned = false
D/RCPManagerService( 2420): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2420): app label == com.android.systemui
,D/RCPManagerService( 2420): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298420
D/RCPManagerService( 2420): getPolicy: policy value returned = true
D/RCPManagerService( 2420): Calling User is -1
,D/RCPManagerService( 2420): userid of SBN ==-1,
D/UserManagerService( 2420): User -1does not exists!!
E/PersonaManagerService( 2420): returning null in  getPersonasForUser
,D/ProgressBar( 2582): setProgressDrawable drawableHeight = 12,
,D/PhoneStatusBar( 2582): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422d7718,
,D/BatteryMeterView( 2582): onDraw batteryColor : -1,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/SensorService( 2420):   0.3 0.0 9.9,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/PowerManagerService( 2420): [s] UserActivityState : 1 -> 2,
,D/DisplayPowerController( 2420): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
,D/PowerManagerService( 2420): [s] mDisplayPowerControllerCallbacks : onStateChanged(),
,D/lights  ( 2420): lcd : 2 +,
D/RampAnimator( 2420): Light Animator Finished currentValue=2
,D/lights  ( 2420): lcd : 2 -,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,D/SensorService( 2420):   0.3 0.0 9.9,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 -0.0 9.9,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2420): [s] UserActivityState : 2 -> 0,
I/PowerManagerService( 2420): [PWL] On : 186670 (39932 ms ago)
I/PowerManagerService( 2420): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2420): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2582, ws=null) (elapsedTime=9882)
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5962): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5962): Breath 70768 latestRequest time : 1450100403342 current time : 1450100474110,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/SensorService( 2420):   0.3 -0.0 9.9,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 7,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2582): GC_CONCURRENT freed 15638K, 34% free 33947K/50844K, paused 25ms+11ms, total 117ms,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2420):   0.3 -0.0 9.9,
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2582 (0x0)
,I/PowerManagerService( 2420): Nap time...
D/PowerManagerService( 2420): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2420): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2420): Going to sleep due to screen timeout...
,D/PowerManagerService( 2420): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/DisplayPowerController( 2420): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2420): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/Sensors ( 2420): LightSensor enable = 0
D/Sensors ( 2420): LightSensor enableSensor = 0
I/SurfaceFlinger( 1922): id=21 createSurf (720x1280),-1 flag=20004, FlectronBea
D/SensorManager( 2420): unregisterListener ::   
,I/Sensors ( 2420): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2420): !@ElectronBeam entry
,D/SensorManager( 2420): unregisterListener ::   
,D/lights  ( 2420): lcd : 0 +
,D/lights  ( 2420): lcd : 0 -
D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2420): blankAllDisplays() is called.
V/WindowOrientationListener( 2420): WindowOrientationListener disabled
D/SensorService( 2420): AutoRotationSensor::activate (ident=0x7b85e300, enabled=0)
I/Sensors ( 2420): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2420): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/input/input0/enabled: 0
,D/KeyguardViewMediator( 2582): onScreenTurnedOff(3)
D/PowerManagerService( 2420): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService( 2420): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 2420): [PWL] sb release: PowerManagerService.Display
D/SensorManager( 2420): unregisterListener ::   
D/InputDispatcher( 2420): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2420): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2420): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2420): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2420): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SurfaceFlinger( 1922): Screen released, type=0 flinger=0x41ef1550
D/PowerManagerService( 2420): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SurfaceControl( 2420): Excessive delay in blankDisplay() while turning screen off: 211ms
,I/libsuspend( 2420): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2420): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2420): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 212ms
D/PowerManagerService( 2420): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2420): [PWL] Off : 0s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2420, ws=null) (elapsedTime=211)
I/PowerManagerService( 2420): [PWL]   PowerManagerService.Broadcasts: ref count=1
,I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2582): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2420): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2420) 
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000,
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
,D/Sensors ( 2420): LightSensor enableSensor = 1,
D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
D/BatteryService( 2420): turn on LED for fully charged
D/VibratorService( 2420): JNI vibratorOff()
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false,
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/STATUSBAR-NotificationService( 2420): ACTION_SCREEN_OFF
D/LightsService( 2420): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2420) 
,D/LightsService( 2420): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2420): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2420): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2420): Bridge Server is not available
,D/PersonaManagerService( 2420): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2420): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2582): makeExpandedInvisible
D/PhoneStatusBarView( 2582): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2582):      ACTION_SCREEN_OFF is finished!!!! 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
I/NfcService( 2764): applyRouting return - 2 
E/NfcService( 2764): callback == null
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2582): isPcwEnable = 10
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5219): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5219): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 5219): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
V/QuickConnect[1.1][2] ( 5219): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229e788
,D/QuickConnect[1.1][2] ( 5219): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5219): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 5219): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5219): stopLeScan()
,D/QuickConnect[1.1][2] ( 5219): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7221): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7221): power? : true / screen off : true
D/PowerManagerService( 2420): [PWL] sb release: PowerManagerService.Broadcasts
,D/TranscodeService( 7221): Music is = false
,D/TranscodeService( 7221): runvideoplayer is false
,D/TranscodeService( 7221): Thread start
D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 5
D/SensorManager( 2420): unregisterListener ::   
D/lights  ( 2420): led_pattern : 5 +
D/TranscodeService( 7221): WakeLock.acquire()
D/videowall-FileMgr( 7221): thumbnailDBSync -1
,D/lights  ( 2420): led_pattern : 5 -
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 2724): GC_EXPLICIT freed 361K, 28% free 9975K/13808K, paused 14ms+7ms, total 68ms
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onInitialize : 330
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onSetOnInfoListener : add 330
I/PrGenericPlugin( 1925): [A] ENTER onInitialize : 0x14a
,I/PrGenericPlugin( 1925): [A] LEAVE onInitialize : 0x14a
,D/TranscodeService( 7221): Thread end
,D/TranscodeService( 7221): WakeLock.release()
D/TranscodeService( 7221): onDestroy()
,D/TranscodeService( 7221): releaseTranscodeThread.
,V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2420): Killing 6646:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/AmoledAdjustTimer( 2420): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
,D/KeyguardViewMediator( 2582): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2582): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2582): isPcwEnable = 10,
D/LockPatternUtils( 2582): isPcwEnable = 10
,D/KeyguardViewMediator( 2582): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2420): [PWL] Off : 5s ago,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 15s ago,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/AlarmManager( 2420): waitForAlarm result :8
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,E/Watchdog( 2420): !@Sync 8,
,D/AmoledAdjustTimer( 2420): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2420): stay LED for fully charged,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2420): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5962): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5962): Breath 111328 latestRequest time : 1450100403342 current time : 1450100514670,
,D/AmoledAdjustTimer( 2420): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2420): waitForAlarm result :8,
,D/Headlines( 5962): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5962): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5962): Breath 130786 latestRequest time : 1450100403342 current time : 1450100534128
,D/Headlines( 5962): stop ,
,D/Headlines( 5962): Breath.onDestroy : ,
,I/ActivityManager( 2420): Killing 6658:com.android.musicfx/u0a24 (adj 15): empty #43,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 50s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = -10
,E/Watchdog( 2420): !@Sync 9,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2420): initializing...,
I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32,
,I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): device_id = 0x0
I/TZ: mc_tlc_communication( 2420): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2420): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI
,I/PowerManagerService( 2420): [PWL] Off : 75s ago
,I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2420, ws=null) (elapsedTime=44),
,I/TZ: mc_tlc_communication( 2420): Opening the session,
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/AmoledAdjustTimer( 2420): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :8,
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 105s ago,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2420): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2420): !@Sync 11,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2420): waitForAlarm result :4,
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/SELinux ( 7988): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7988):  
,I/SELinux ( 7988): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7988):  
I/SELinux ( 7988):  
,I/SELinux ( 7988): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7988): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 7988): >>>>> Normal User
,E/dalvikvm( 7988): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7988): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7988): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7988): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7988): Added TimaKesytore provider
,D/dalvikvm( 7988): GC_CONCURRENT freed 3009K, 31% free 9556K/13828K, paused 2ms+1ms, total 27ms,
,D/dalvikvm( 7988): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2420): Killing 6686:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43,
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true,
,D/BatteryService( 2420): stay LED for fully charged,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2420): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2420): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 12
,D/AmoledAdjustTimer( 2420): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,I/jxcore-log( 6808): Connected to the server!
I/jxcore-log( 6808): 
,I/chromium( 6808): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 13
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 2420): GC_CONCURRENT freed 3292K, 74% free 25921K/99132K, paused 26ms+24ms, total 305ms
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 14
,D/AmoledAdjustTimer( 2420): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 225s ago
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 15
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 16
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 275s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 17,
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 18
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 19
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2420): !@Sync 20
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2420): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 21
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5724): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5724): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 22
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 23
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 24
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4081): GC_CONCURRENT freed 2882K, 30% free 9723K/13868K, paused 6ms+3ms, total 57ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 25
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 26
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 27
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 28
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 9706
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2420): GC_CONCURRENT freed 4061K, 74% free 25873K/98868K, paused 20ms+18ms, total 242ms
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2420): !@Sync 29
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2420, ws=null) (elapsedTime=5090)
,E/Watchdog( 2420): !@Sync 30
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 32
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 34
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :4
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2420): LightSensor setDelay = 200000000
,D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5622): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5622): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,E/Watchdog( 2420): !@Sync 39
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 40
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 41
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 44
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_FOR_ALLOC freed 3974K, 74% free 25989K/98868K, paused 213ms, total 213ms
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 238K, 74% free 25821K/98868K, paused 10ms+18ms, total 212ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 46
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 48
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4081): GC_CONCURRENT freed 2050K, 30% free 9721K/13868K, paused 2ms+2ms, total 27ms
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 49
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 11631
W/ProcessCpuTracker( 2420): Skipping unknown process pid 11636
W/ProcessCpuTracker( 2420): Skipping unknown process pid 11641
W/ProcessCpuTracker( 2420): Skipping unknown process pid 11646
W/ProcessCpuTracker( 2420): Skipping unknown process pid 11649
W/ProcessCpuTracker( 2420): Skipping unknown process pid 11651
W/ProcessCpuTracker( 2420): Skipping unknown process pid 11652
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 11653
,E/Watchdog( 2420): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 51
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 52
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 54
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 56
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 58
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2420): GC_CONCURRENT freed 3923K, 74% free 25930K/98868K, paused 13ms+19ms, total 261ms
,E/Watchdog( 2420): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 59ms
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-56-19.bin
,I/ProcessStatsService( 2420): Prepared write state in 28ms
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 61
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 62
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 64
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
I/ActivityManager( 2420): Killing 6489:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1808s
,I/ActivityManager( 2420): Killing 6890:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1808s
,I/ActivityManager( 2420): Killing 6873:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1809s
,I/ActivityManager( 2420): Killing 6849:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1810s
,I/ActivityManager( 2420): Killing 6821:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1810s
,I/ActivityManager( 2420): Killing 6794:com.samsung.helphub/1000 (adj 15): empty for 1810s
,I/ActivityManager( 2420): Killing 6781:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1810s
,I/ActivityManager( 2420): Killing 6761:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1811s
,I/ActivityManager( 2420): Killing 6745:com.sec.android.service.cm/u0a82 (adj 15): empty for 1811s
,I/ActivityManager( 2420): Killing 6460:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1811s
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2420): Killing 5785:com.android.mms/u0a49 (adj 15): empty for 1811s
,I/ActivityManager( 2420): Killing 6720:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1811s
,I/ActivityManager( 2420): Killing 6090:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1812s
,D/CountryDetector( 2420): No listener is left
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,TIME-OUT KILL (timeout was 1800000ms),D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
D/AndroidRuntime(13080): 
D/AndroidRuntime(13080): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13080): CheckJNI is OFF
D/AndroidRuntime(13080): setted country_code = Poland
D/AndroidRuntime(13080): setted countryiso_code = PL
D/AndroidRuntime(13080): setted sales_code = PLS
D/AndroidRuntime(13080): readGMSProperty: start
D/AndroidRuntime(13080): readGMSProperty: already setted!!
D/AndroidRuntime(13080): readGMSProperty: end
D/AndroidRuntime(13080): addProductProperty: start
D/dalvikvm(13080): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13080): Added shared lib libjavacore.so 0x0
D/dalvikvm(13080): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13080): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13080): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13080): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13080): failed to load memtrack module: -2
D/dalvikvm(13080): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13080): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2420): START PACKAGE DELETE: observer{1116811096}
D/PackageManager( 2420): pkg{<packageName>}
D/PackageManager( 2420): user{0}
D/PackageManager( 2420): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2420): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2420): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2420): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2420): !@killApplicatoin: 10536, uninstall pkg
I/ActivityManager( 2420): Killing 6808:com.test.thalitest/u0a536 (adj 0): stop com.test.thalitest
I/ActivityManager( 2420): Killing 7233:com.sec.android.app.voicenote/1000 (adj 15): empty for 1810s
I/ActivityManager( 2420): Killing 7043:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1810s
I/ActivityManager( 2420): Killing 5894:com.osp.app.signin/u0a44 (adj 15): empty for 1810s
I/ActivityManager( 2420): Killing 6700:com.policydm/1000 (adj 15): empty for 1810s
I/ActivityManager( 2420): Killing 7018:com.sec.android.soagent/u0a38 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 6942:com.vlingo.midas/u0a34 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 7006:com.samsung.klmsagent/u0a18 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 6987:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 5836:com.sec.android.diagmonagent/1000 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 6671:com.sec.pcw.device/1000 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 7195:com.sec.knox.bridge/1000 (adj 15): empty for 1811s
I/ActivityManager( 2420): Killing 7183:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1812s
I/ActivityManager( 2420): Killing 4762:com.android.settings/1000 (adj 15): empty for 1812s
I/ActivityManager( 2420): Killing 7149:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1812s
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
I/WindowState( 2420): WIN DEATH: Window{473e3d20 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 2420): Skipping PackageSetting{42c62fe8 com.example.hello/10511} due to missing metadata
D/PackageManager( 2420): setPackageStoppedState - Execution time: 105 ms
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10536, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6512): GC_EXPLICIT freed 250K, 28% free 9981K/13836K, paused 5ms+3ms, total 39ms
I/DBG_DM  ( 4787): [3.19.140541][Line:408][onResume] 
D/PackageManager( 2420): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10536, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/DBG_DM  ( 4787): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
D/dalvikvm( 3284): GC_EXPLICIT freed 1117K, 22% free 12434K/15864K, paused 9ms+10ms, total 88ms
D/dalvikvm( 2964): GC_EXPLICIT freed 1469K, 28% free 10033K/13828K, paused 8ms+5ms, total 80ms
I/DBG_DM  ( 4787): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader( 2420): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 4787): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
E/SamsungIME( 2991): mOCRHelper is null
I/DBG_DM  ( 4787): [3.19.140541][Line:418][onResume] Postpone Count : 26
D/QuickConnect[1.1][2] ( 5219): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/DBG_DM  ( 4787): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/SELinux (13115): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13115):  
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13115): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13115):  
I/SELinux (13115):  
I/SELinux (13115): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13115): >>>>> Normal User
E/dalvikvm(13115): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/DBG_DM  ( 4787): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
D/TimaKeyStoreProvider(13115): in addTimaSignatureService
I/DBG_DM  ( 4787): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
D/RegisteredServicesCache( 2764): empty dynamic service
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(13115): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13115): Added TimaKesytore provider
I/DBG_DM  ( 4787): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
I/DBG_DM  ( 4787): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
I/DBG_DM  ( 4787): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4787): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4787): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4787): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4787): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/dalvikvm( 2420): GC_EXPLICIT freed 3604K, 75% free 25197K/98868K, paused 10ms+28ms, total 286ms
D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 224ms
D/dalvikvm( 2771): GC_CONCURRENT freed 8897K, 40% free 18299K/30164K, paused 7ms+12ms, total 99ms
D/dalvikvm( 2771): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
D/Activity( 4787): setTransGradationMode to true
D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/StatusBarManagerService( 2420): semi p:4787,o:t
I/DBG_DM  ( 4787): [3.19.140541][Line:400][onPause] 
I/SurfaceFlinger( 1922): id=22 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2420): PackageReceiver onReceive()
I/HarmonyEASService( 2420): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm(13115): GC_CONCURRENT freed 2989K, 31% free 9574K/13828K, paused 3ms+1ms, total 23ms
D/dalvikvm(13115): WAIT_FOR_CONCURRENT_GC blocked 14ms
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2420): Got RemoteException sending setActive(false) notification to pid 6808 uid 10536
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/ActivityManager( 2420): mDVFSHelper.release()
D/dalvikvm( 2764): GC_CONCURRENT freed 2330K, 26% free 10255K/13840K, paused 11ms+3ms, total 92ms
D/EnterpriseDeviceManagerService( 2420): Package has changed for user 0
D/elm:14132(13115): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13115): ELMEngine.ELMEngine( context ).
D/elm:14132(13115): MDMBridge.setEnterpriseBridge()
D/elm:14132(13115): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/SELinux (13128): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13128):  
D/elm:14132(13115): ElmAgentService : onCreate()
D/elm:14132(13115): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13115): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13115): MDMBridge.getInstance()
D/elm:14132(13115): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13115): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13115): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(13115): ElmAgentService : onDestroy().
I/SELinux (13128): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13128):  
I/SELinux (13128):  
I/SELinux (13128): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13128): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13128): >>>>> Normal User
E/dalvikvm(13128): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
I/ActivityManager( 2420): Killing 7056:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1811s
E/SELinux (13128): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13128): in addTimaSignatureService
D/TimaKeyStoreProvider(13128): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13128): Added TimaKesytore provider
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2420): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2420): removePackageParticipantsLocked: uid=10536 #1
D/dalvikvm(13128): GC_CONCURRENT freed 2993K, 31% free 9566K/13824K, paused 5ms+1ms, total 36ms
D/dalvikvm(13128): WAIT_FOR_CONCURRENT_GC blocked 31ms
W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2420): sendNotification(2) - 4
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2420): GC_EXPLICIT freed 1287K, 75% free 25219K/98868K, paused 13ms+30ms, total 493ms
I/SELinux (13146): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13146):  
I/ActivityManager( 2420): Killing 7130:com.android.email/u0a157 (adj 15): empty for 1811s
I/SELinux (13146): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13146):  
I/SELinux (13146):  
I/SELinux (13146): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13146): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13146): >>>>> Normal User
E/dalvikvm(13146): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (13146): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13146): in addTimaSignatureService
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13146): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13146): Added TimaKesytore provider
D/PackageManager( 2420): delete sourFile : 
D/PackageManager( 2420): delete native library directory: 
D/PackageManager( 2420): return delete result to caller: 1116811096
D/AndroidRuntime(13080): Shutting down VM
D/PackageManager( 2420): returnCode: 1
D/dalvikvm(13146): GC_CONCURRENT freed 2997K, 31% free 9566K/13828K, paused 2ms+1ms, total 22ms
D/dalvikvm(13146): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm(13080): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "sms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "smsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mms"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2420):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2420):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2420):   Scheme: "mmsto"
I/PackageManager( 2420): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13158): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13158):  
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2420): Killing 7162:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1811s
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2420): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2420): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2420): clearDefaults: com.test.thalitest
I/SELinux (13158): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13158):  
I/SELinux (13158):  
I/SELinux (13158): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13158): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13158): >>>>> Normal User
E/dalvikvm(13158): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13158): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13158): in addTimaSignatureService
D/TimaKeyStoreProvider(13158): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13158): Added TimaKesytore provider
W/ApplicationsProvider( 2964): Could not fetch usage stats
W/ApplicationsProvider( 2964): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2964): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2964): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2964): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2964): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2964): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2964): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm(13158): GC_CONCURRENT freed 3011K, 31% free 9553K/13828K, paused 2ms+2ms, total 21ms
D/dalvikvm(13158): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/SELinux (13172): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13172):  
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9501K/10808K, paused 3ms+3ms, total 32ms
I/SELinux (13172): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13172):  
I/SELinux (13172):  
I/SELinux (13172): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13172): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13172): >>>>> Normal User
E/dalvikvm(13172): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13172): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13172): Enabling JNI app bug workarounds for target SDK version 8...
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 2ms+3ms, total 26ms
D/TimaKeyStoreProvider(13172): in addTimaSignatureService
D/TimaKeyStoreProvider(13172): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13172): Added TimaKesytore provider
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10808K, paused 2ms+3ms, total 24ms
I/ActivityManager( 2420): Killing 5475:com.google.android.talk/u0a109 (adj 15): empty for 1812s
D/dalvikvm(13172): GC_CONCURRENT freed 3003K, 31% free 9565K/13828K, paused 2ms+1ms, total 19ms
D/dalvikvm(13172): WAIT_FOR_CONCURRENT_GC blocked 17ms
E/SQLiteDatabase(13172): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13172): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13172): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13172): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13172): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13172): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13172): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13172): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13172): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13172): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13172): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13172): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13172): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13172): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13172): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13172): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13172): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13172): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13172): Shutting down VM
W/dalvikvm(13172): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13172): FATAL EXCEPTION: main
E/AndroidRuntime(13172): Process: com.sec.pcw.device, PID: 13172
E/AndroidRuntime(13172): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13172): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13172): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13172): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13172): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13172): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13172): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13172): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13172): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13172): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13172): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13172): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13172): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13172): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13172): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13172): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13172): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13172): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13172): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13172): 	... 12 more
E/DropBoxManagerService( 2420): Can't write: system_app_crash
E/DropBoxManagerService( 2420): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (13187): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13187):  
I/Process (13172): Sending signal. PID: 13172 SIG: 9
I/ActivityManager( 2420): Process com.sec.pcw.device (pid 13172) (adj 0) has died.
I/SELinux (13187): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13187):  
I/SELinux (13187):  
I/SELinux (13187): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13187): >>>>> Normal User
E/dalvikvm(13187): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13187): in addTimaSignatureService
D/TimaKeyStoreProvider(13187): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13187): Added TimaKesytore provider
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
E/Watchdog( 2420): !@Sync 65
D/dalvikvm(13187): GC_CONCURRENT freed 3008K, 31% free 9561K/13832K, paused 2ms+2ms, total 19ms
D/dalvikvm(13187): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/System.err(13187): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13187): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13187): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13187): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13187): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13187): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13187): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13187): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13187): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13187): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13187): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13187): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13187): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13187): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13187): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13187): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13187): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13187): 	at libcore.io.Posix.open(Native Method)
W/System.err(13187): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13187): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13187): 	... 21 more
D/GalaxyFinderApplication(13187): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13187): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13201): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13201):  
I/ActivityManager( 2420): Killing 6048:com.sec.android.app.samsungapps/u0a41 (adj 15): empty for 1802s
I/SELinux (13201): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13201):  
I/SELinux (13201):  
I/SELinux (13201): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13201): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13201): >>>>> Normal User
E/dalvikvm(13201): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13201): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13201): in addTimaSignatureService
D/TimaKeyStoreProvider(13201): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13201): Added TimaKesytore provider
D/dalvikvm(13201): GC_CONCURRENT freed 2994K, 31% free 9566K/13824K, paused 2ms+1ms, total 17ms
D/dalvikvm(13201): WAIT_FOR_CONCURRENT_GC blocked 15ms
W/ContextImpl(13201): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13201): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13201): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13201): ContentProvider is not null
W/ResourceType(13201): No package identifier when getting value for resource number 0x00000000

```
