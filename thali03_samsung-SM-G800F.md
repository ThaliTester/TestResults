#### Test 50650278eab32a5_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 6628): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6628): Added TimaKesytore provider
D/dalvikvm( 6612): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422fcf20, skipping init
D/dalvikvm( 6628): GC_CONCURRENT freed 2990K, 32% free 9567K/13944K, paused 2ms+1ms, total 27ms
D/dalvikvm( 6628): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/SecureStorage( 6612): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)Credentials: uid 1000, gid 1000, pid 6612
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)Received function mask & code: 00000106
--------- beginning of /dev/log/system
D/SSRMv2:SIOP( 2419): SIOP:: AP = 350, Delta = 0
D/ActivityThread( 6628): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6628): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6628): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SA      ( 5798): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5798): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5798): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5684): loadAuthorityPref(): sEnableAuthority = true
I/Icing.InternalIcingCorporaProvider( 6419): Updating corpora: A: com.test.thalitest, C: MAYBE
W/ContextImpl( 6350): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 6658): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6658):  
I/SELinux ( 6658): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6658):  
I/SELinux ( 6658):  
I/SELinux ( 6658): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6658): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6658): >>>>> Normal User
E/dalvikvm( 6658): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6658): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6658): in addTimaSignatureService
D/TimaKeyStoreProvider( 6658): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6658): Added TimaKesytore provider
D/dalvikvm( 6658): GC_CONCURRENT freed 3000K, 32% free 9567K/13952K, paused 4ms+1ms, total 48ms
D/dalvikvm( 6658): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/CapabilityManagerService New( 6658): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/SELinux ( 6671): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6671):  
I/ActivityManager( 2419): Killing 5319:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
I/SELinux ( 6671): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6671):  
I/SELinux ( 6671):  
I/SELinux ( 6671): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6671): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6671): >>>>> Normal User
E/dalvikvm( 6671): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6671): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6671): in addTimaSignatureService
D/TimaKeyStoreProvider( 6671): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6671): Added TimaKesytore provider
D/dalvikvm( 3423): GC_CONCURRENT freed 2032K, 22% free 12454K/15864K, paused 5ms+13ms, total 155ms
I/Icing.InternalIcingCorporaProvider( 6419): UpdateCorporaTask done [took 363 ms] updated apps [took 363 ms] 
I/ActivityManager( 2419): Killing 5753:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
D/dalvikvm( 6671): GC_CONCURRENT freed 2998K, 32% free 9564K/13948K, paused 3ms+1ms, total 21ms
D/dalvikvm( 6671): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/PackageIntentReceiver( 6671): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6671): Not GearManger package! 
I/SELinux ( 6686): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6686):  
I/ActivityManager( 2419): Killing 5562:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 6686): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6686):  
I/SELinux ( 6686):  
I/SELinux ( 6686): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6686): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6686): >>>>> Normal User
E/dalvikvm( 6686): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6686): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1960): [INFO]: SPID(0x00000006)PID: 6612, TID: 6624
D/TimaKeyStoreProvider( 6686): in addTimaSignatureService
D/TimaKeyStoreProvider( 6686): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6686): Added TimaKesytore provider
D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
D/dalvikvm( 6686): GC_CONCURRENT freed 2995K, 32% free 9571K/13948K, paused 2ms+1ms, total 20ms
D/dalvikvm( 6686): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/MagazineService Version( 6686): Magazine-Channel: 13
D/MagazineService Version( 6686): Magazine-Provider: 13
D/MagazineService Version( 6686): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 6686): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 6686): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
I/MagazineService::MagazineService( 6686): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 6699): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6699):  
D/AndroidRuntime( 6683): 
D/AndroidRuntime( 6683): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6683): CheckJNI is OFF
D/AndroidRuntime( 6683): setted country_code = Poland
D/AndroidRuntime( 6683): setted countryiso_code = PL
D/AndroidRuntime( 6683): setted sales_code = PLS
D/AndroidRuntime( 6683): readGMSProperty: start
D/AndroidRuntime( 6683): readGMSProperty: already setted!!
D/AndroidRuntime( 6683): readGMSProperty: end
D/AndroidRuntime( 6683): addProductProperty: start
D/MagazineService::MagazineService( 6686): [onHandleIntent] Send broadcast to (com.test.thalitest).
D/dalvikvm( 6683): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 14% free 9500K/10928K, paused 3ms+3ms, total 36ms
D/dalvikvm( 1922): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/SELinux ( 6699): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6699):  
I/SELinux ( 6699):  
I/SELinux ( 6699): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6699): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6699): >>>>> Normal User
E/dalvikvm( 6699): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
D/dalvikvm( 6683): Added shared lib libjavacore.so 0x0
E/SELinux ( 6699): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 6683): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6683): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6683): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SecureStorage( 6612): [INFO]: SPID(0x00000000)Processing data has been completed
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9500K/10928K, paused 1ms+3ms, total 23ms
I/ActivityManager( 2419): Killing 6012:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/TimaKeyStoreProvider( 6699): in addTimaSignatureService
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9500K/10928K, paused 2ms+3ms, total 24ms
D/TimaKeyStoreProvider( 6699): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6699): Added TimaKesytore provider
D/dalvikvm( 6699): GC_CONCURRENT freed 3004K, 32% free 9567K/13952K, paused 3ms+2ms, total 23ms
D/dalvikvm( 6699): WAIT_FOR_CONCURRENT_GC blocked 15ms
E/memtrack( 6683): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6683): failed to load memtrack module: -2
D/dalvikvm( 6683): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6683): Calling main entry com.android.commands.am.Am
I/SELinux ( 6721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6721):  
I/ActivityManager( 2419): Killing 5768:com.sec.android.soagent/u0a38 (adj 15): empty #43
I/SELinux ( 6721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6721):  
I/SELinux ( 6721):  
I/SELinux ( 6721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6721): >>>>> Normal User
E/dalvikvm( 6721): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
E/SELinux ( 6721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6721): in addTimaSignatureService
D/TimaKeyStoreProvider( 6721): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6721): Added TimaKesytore provider
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SELinux ( 6733): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6733):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6683): Shutting down VM
D/dalvikvm( 6683): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
D/dalvikvm( 6721): GC_CONCURRENT freed 2997K, 32% free 9567K/13948K, paused 2ms+1ms, total 18ms
D/dalvikvm( 6721): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/SELinux ( 6733): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6733):  
I/SELinux ( 6733):  
I/SELinux ( 6733): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6733): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6733): >>>>> Normal User
E/dalvikvm( 6733): >>>>> com.test.thalitest [ userId:0 | appId:10520 ]
E/SELinux ( 6733): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/KidsPlatformStub( 6721): Package not found : com.sec.android.app.kidshome
D/TimaKeyStoreProvider( 6733): in addTimaSignatureService
I/SELinux ( 6745): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6745):  
D/TimaKeyStoreProvider( 6733): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6733): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 6106:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
I/SELinux ( 6745): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6745):  
I/SELinux ( 6745):  
I/SELinux ( 6745): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6745): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6745): >>>>> Normal User
E/dalvikvm( 6745): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
E/SELinux ( 6745): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SQLiteSecureOpenHelper( 4174): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4174): getDatabaseLocked(b,b,pwd)...
D/TimaKeyStoreProvider( 6745): in addTimaSignatureService
D/TimaKeyStoreProvider( 6745): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6745): Added TimaKesytore provider
D/dalvikvm( 6733): GC_CONCURRENT freed 3001K, 32% free 9567K/13952K, paused 2ms+1ms, total 19ms
D/dalvikvm( 6733): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 6745): GC_CONCURRENT freed 2998K, 32% free 9567K/13948K, paused 3ms+1ms, total 21ms
D/dalvikvm( 6745): WAIT_FOR_CONCURRENT_GC blocked 14ms
,V/WebViewChromium( 6733): Binding Chromium to the background looper Looper (main, tid 1) {422a7298}
,I/chromium( 6733): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6733): Initializing chromium process, renderers=0
,I/SELinux ( 6758): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6758):  
,I/ActivityManager( 2419): Killing 5848:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
I/Icing   ( 3423): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,W/chromium( 6733): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SELinux ( 6758): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6758):  
I/SELinux ( 6758):  
,I/SELinux ( 6758): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6758): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6758): >>>>> Normal User
,E/dalvikvm( 6758): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6758): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/libEGL  ( 6733): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6733): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/TimaKeyStoreProvider( 6758): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6758): Cannot add TimaSignature Service, License check Failed
,D/libEGL  ( 6733): loaded /system/lib/egl/libGLESv2_mali.so
,D/ActivityThread( 6758): Added TimaKesytore provider
,I/Mali    ( 6733): Mali API Version : 401
,I/Mali    ( 6733): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6733): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6733): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 6733): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6733): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6733): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6733): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2577): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): tr p:6733,o:f
W/dalvikvm( 6733): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6733): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6733): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6733): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6733): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 6733): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6733): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6733): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 6733): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6733): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6733): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 6733): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 6733): CordovaWebView is running on device made by: samsung
,D/dalvikvm( 6758): GC_CONCURRENT freed 3002K, 32% free 9564K/13948K, paused 3ms+1ms, total 29ms
,D/dalvikvm( 6758): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Icing   ( 3423): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/PhoneStatusBar( 2577): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:6733,o:f
,D/UMC:Core( 6758): onCreate(): 
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
I/HWUI    ( 6733): EGLImpl-HWUI Protected EGL context created
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,D/OpenGLRenderer( 6733): Enabling debug mode 0
,W/AwContents( 6733): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,W/AwContents( 6733): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 6733): showStatusIcon on inactive InputConnection
,D/USER_AGENT( 6758): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/[SAMSUNG SMARCART NATIVE]( 6758): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6758): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/TZ_CCM_C_GetFunctionList: ( 6758): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6758): FINISHED: initialize rv:0
,D/JsMessageQueue( 6733): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6758): GC_CONCURRENT freed 1867K, 24% free 10769K/14016K, paused 3ms+2ms, total 41ms
,D/dalvikvm( 6758): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/UMC:SecurityUtils( 6758): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6758): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6758): New Flow
I/        ( 2419): CCM JNI: In ccm_register_for_default_cert
,I/        ( 2419): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2419): &ctx = 0x77ac8618
I/TLC_TZ_CCM: ( 2419): creating new ccm context...
I/TLC_TZ_CCM: ( 2419): initializing ccm context...
I/TLC_TZ_CCM: ( 2419): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2419): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2419): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2419): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2419): root = 0, root_len = 1
I/TZ: client_server_communication( 2419): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2419): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2419): aligned max_recvmsg_size = 19456
,I/TZ: client_server_communication( 2419): Client_Server_Open was called
I/TZ: client_server_communication( 2419): IClientServer::IClientServer()
,I/TZ: client_server_communication( 2419): BpClientServer::BpClientServer()
D/TimaService( 2419): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2419): TIMA: in getTimaVersion
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
,I/TZ: client_server_communication( 2419): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2419): ctx = 0x72914648, comm = 0x87739e58, sendmsg = 0x7fa3c2b8, recvmsg = 0x7fa40eb8
I/TZ_init: ( 2419): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,E/Parcel  ( 2419): nm 19456
E/TZ_init: ( 2419): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2419): trustlet initialization failed
,I/TZ_init: ( 2419): TZ_init_START...
,I/TZ_init: ( 2419): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456
,E/Parcel  ( 2419): nm 19456
,I/TZ_init: ( 2419): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2419): Exercising TZ_DB_INIT in TLC
,I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456,
E/Parcel  ( 2419): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2419): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: ( 2419): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16
,E/Parcel  ( 2508): nm 19456,
E/Parcel  ( 2419): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2419): TZ_CCM_register_default_TLC_END: DB file size to update is 0,
I/TLC_TZ_CCM: register for default cert: ( 2419): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2419): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(2) 16,
,E/Parcel  ( 2508): nm 19456,
E/Parcel  ( 2419): nm 19456,
I/TZ: client_server_communication( 2419): Client_Server_Close was called,
I/TZ_CCM_SERVER( 2508): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2508): tlc_close() was called,
,I/TZ: mc_tlc_communication( 2508): Closing the session
,D/dalvikvm( 6733): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4229f830
,I/TZ: mc_tlc_communication( 2508): Free WSM
,I/TZ: mc_tlc_communication( 2508): Closing MobiCore device
,D/dalvikvm( 6733): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4229f830
,D/jxcore_app_log( 6733): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027479848
,D/JX-Cordova( 6733): jxcore cordova android initializing
,I/TZ: mc_tlc_communication( 2508): tlc_close() succeeded
,I/TZ: client_server_communication( 2419): Client_Server_Close succeeded
I/dalvikvm( 6733): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 6733): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6733): VFY: replacing opcode 0x6e at 0x0045
,D/UMC:CloudMDMSecurity( 6758): TIMA service call for password change success!!
,D/UMC:AdminManager( 6758): init - start
,D/UMC:AdminManager( 6758): loadAdmins
,D/UMC:AdminManager( 6758): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6758): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6758): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6758): init - end
,V/UMC:AlarmHandler( 6758): Enter loadList
,D/EnterpriseDeviceManagerService( 2419): Creating context as user 0
,D/SPPApp  ( 6758): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6758): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6804): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6804):  
,I/ActivityManager( 2419): Killing 6122:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,I/SELinux ( 6804): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6804):  
I/SELinux ( 6804):  
,I/SELinux ( 6804): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6804): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6804): >>>>> Normal User
,E/dalvikvm( 6804): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6804): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6804): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6804): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6804): Added TimaKesytore provider
,D/dalvikvm( 6804): GC_CONCURRENT freed 2998K, 32% free 9571K/13952K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 6804): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 6733): GC_CONCURRENT freed 1292K, 20% free 11349K/14020K, paused 2ms+3ms, total 29ms
D/dalvikvm( 6733): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 6733): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/ApplicationPromenada( 6804): Application OnCreate start
,D/ApplicationPromenada( 6804): Application OnCreate po on Create
D/CrashReporter( 6804): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@422ae2e0
D/CrashReporter( 6804): Swaping uncaught exception handler
,D/ApplicationPromenada( 6804): Application OnCreate App Loader start
,D/ApplicationPromenada( 6804): Application OnCreate App Loader finish
,D/p2.ApplicationLoader( 6804): ############################## cached apps: 
,V/WebViewChromium( 6804): Binding Chromium to the background looper Looper (main, tid 1) {422aa0f8}
,I/chromium( 6804): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6804): Initializing chromium process, renderers=0
,W/chromium( 6804): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6804): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6804): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6804): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6804): Mali API Version : 401
,I/Mali    ( 6804): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6804): Application OnCreate Finish
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,I/ActivityManager( 2419): Killing 6134:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/PackageBroadcastService( 3423): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3423): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3423): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3423): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3423): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3423): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3423): Submit a task: k
,D/ChimeraCfgMgr( 3423): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3423): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3423): Processing package: com.test.thalitest
,D/dalvikvm( 6733): GC_CONCURRENT freed 1954K, 19% free 14926K/18272K, paused 2ms+9ms, total 93ms
,D/dalvikvm( 6733): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/GassUtils( 3423): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3423): Found info for package com.test.thalitest in db.
,D/Finsky  ( 3684): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 6804): GC_CONCURRENT freed 1766K, 23% free 10830K/13960K, paused 3ms+7ms, total 51ms
,D/dalvikvm( 6733): GC_FOR_ALLOC freed 5316K, 30% free 16201K/23132K, paused 45ms, total 45ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 6804): GC_CONCURRENT freed 2402K, 27% free 10423K/14212K, paused 2ms+3ms, total 50ms
,W/ResourceType( 6804): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6804): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6804): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6804): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6804): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6804): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6804): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6804): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6804): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6804): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6804): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6804): 	at java.lang.Thread.run(Thread.java:841)
,I/Icing   ( 3423): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3423): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/PowerManagerService( 2419): [PWL] Off : 75s ago
,D/dalvikvm( 6733): GC_CONCURRENT freed 6704K, 32% free 17663K/25772K, paused 2ms+11ms, total 71ms
,D/dalvikvm( 6733): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 6733): WAIT_FOR_CONCURRENT_GC blocked 44ms
,D/dalvikvm( 6804): GC_CONCURRENT freed 2009K, 26% free 10524K/14212K, paused 1ms+2ms, total 44ms
,D/dalvikvm( 6733): GC_FOR_ALLOC freed 1414K, 33% free 17345K/25772K, paused 46ms, total 46ms
,I/dalvikvm-heap( 6733): Grow heap (frag case) to 21.801MB for 3688532-byte allocation
,D/dalvikvm( 6733): GC_FOR_ALLOC freed 2406K, 37% free 18540K/29376K, paused 41ms, total 41ms
,W/jxcore-log( 6733): Initializing JXcore engine
,W/jxcore-log( 6733): JXcore engine is ready
,W/jxcore-log( 6733): Starting JXcore engine
,D/p2.ApplicationLoader( 6804): Process time: 2745
,D/p2.ApplicationLoader( 6804): ##############################  apps after loading: 
,W/jxcore-log( 6733): Platform android
W/jxcore-log( 6733): 
,W/jxcore-log( 6733): Process ARCH arm
W/jxcore-log( 6733): 
,I/jxcore-log( 6733): JXcore Cordova bridge is ready!
I/jxcore-log( 6733): 
,W/jxcore-log( 6733): JXcore engine is started
,I/chromium( 6733): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 6733): Error!: missing ) after argument list
E/jxcore  ( 6733): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6733): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2419): Killing 5306:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.acquire()
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5862): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,I/DBG_DM  ( 4731): [3.19.140541][Line:408][onResume] 
,D/Headlines( 5862): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5862): Breath 72214 latestRequest time : 1449668712450 current time : 1449668784664
,I/DBG_DM  ( 4731): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4731): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4731): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4731): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4731): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4
,I/DBG_DM  ( 4731): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4731): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4731): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4731): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4731): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4731): setTransGradationMode to true
,D/PhoneStatusBar( 2577): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2419): semi p:4731,o:t
I/DBG_DM  ( 4731): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1921): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6733): showStatusIcon on inactive InputConnection
,I/VacuumService( 2733): Vacuum at: now=1449668784892 tag=VacuumService
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2855): GC_CONCURRENT freed 1918K, 24% free 10868K/14236K, paused 7ms+3ms, total 61ms,
,D/dalvikvm( 2419): GC_EXPLICIT freed 25722K, 74% free 25034K/95160K, paused 8ms+19ms, total 239ms,
,I/PhenotypeConfigurator( 2733): Scheduling Phenotype for one-off execution 1630 seconds from now (1449668785582),
,D/GetConfigurationSnapshotOperation( 2733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, ,
,I/PhenotypeFlagCommitter( 2733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader,
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2733): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2733): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2733): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2733): GC_CONCURRENT freed 1817K, 22% free 11681K/14948K, paused 3ms+5ms, total 57ms
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2733): Thread-121(HTTPLog):isShipBuild true
,I/System.out( 2733): Thread-121(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2419): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 360, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/HarmonyEASService( 2419): Updating for all 1
,D/PackageManager( 2419): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@428d50a8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredServicesCache( 2754): empty dynamic service
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/Icing.InternalIcingCorporaProvider( 6419): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/FileShare-Server( 4854): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BezelQuickConnect( 5145): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5145): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,I/Icing.InternalIcingCorporaProvider( 6419): UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageBroadcastService( 3423): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ApplicationsProvider( 2968): Could not fetch usage stats,
W/ApplicationsProvider( 2968): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2968): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2968): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/ApplicationsProvider( 2968): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2968): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2968): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681),
W/ApplicationsProvider( 2968): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2968): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2968): ,	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2968): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Icing   ( 3423): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms,
,I/Icing   ( 3423): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6885,
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6888
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6890
W/ProcessCpuTracker( 2419): Skipping unknown process pid 6892
W/ProcessCpuTracker( 2419): Skipping unknown process pid 6893,
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6898,
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 6900,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Finsky  ( 3684): [187] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 3684): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 340, Delta = -20,
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2419): waitForAlarm result :8,
,D/Headlines( 5862): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5862): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5862): Breath 90036 latestRequest time : 1449668712450 current time : 1449668802486,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2419): !@Sync 5,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 105s ago,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,E/Watchdog( 2419): !@Sync 6,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5862): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5862): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5862): Breath 137299 latestRequest time : 1449668712450 current time : 1449668849749
,D/Headlines( 5862): stop 
,D/Headlines( 5862): Breath.onDestroy : 
,I/ActivityManager( 2419): Killing 6162:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,E/SPPClientService( 5535): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 7,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,E/Watchdog( 2419): !@Sync 8,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2419): !@Sync 9,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2419): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate,
D/BatteryService( 2419): stay LED for fully charged
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2419): !@Sync 10,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,D/dalvikvm( 2419): GC_CONCURRENT freed 3827K, 74% free 24996K/95160K, paused 20ms+21ms, total 258ms,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2419): [PWL] Off : 275s ago,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 11,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7521):  
,I/SELinux ( 7521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7521):  
I/SELinux ( 7521):  
,I/SELinux ( 7521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
,E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7521): >>>>> Normal User
,E/dalvikvm( 7521): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7521): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7521): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7521): Added TimaKesytore provider
,D/dalvikvm( 7521): GC_CONCURRENT freed 3009K, 32% free 9563K/13952K, paused 3ms+2ms, total 29ms,
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 26ms,
,I/ActivityManager( 2419): Killing 6234:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10,
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2419): initializing...
,I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2419): device_id = 0x0
,I/TZ: mc_tlc_communication( 2419): tlc_open() was called
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2419): Opening the session
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 7633
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 12
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 13
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 14
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 15
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 16
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,E/Watchdog( 2419): !@Sync 17
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 18
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 19
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 20
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 21
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/GAV2    ( 5625): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5625): Thread[disconnect check,5,main]: Disconnected from service
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3957K, 74% free 24821K/95040K, paused 19ms+17ms, total 235ms
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 25
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4069): GC_CONCURRENT freed 2893K, 31% free 9723K/13996K, paused 7ms+2ms, total 58ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5535): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2419): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2577): updateDataNetType()
,D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SPPClientService( 5535): [b] __PingReply__
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3727K, 74% free 24848K/95040K, paused 24ms+20ms, total 283ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 40
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,V/AlarmManager( 2419): waitForAlarm result :4
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
,D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3423): Aggregate from 1449668330669 (log), 1449668330669 (data)
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4069): GC_CONCURRENT freed 2050K, 31% free 9720K/13996K, paused 4ms+4ms, total 51ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 5535): GC_CONCURRENT freed 1898K, 26% free 10420K/13940K, paused 7ms+4ms, total 69ms
,E/Watchdog( 2419): !@Sync 50
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3755K, 74% free 24870K/95040K, paused 24ms+18ms, total 257ms
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5535): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 60
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 61ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-44.bin
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2419): waitForAlarm result :4
,V/NetworkStats( 2419): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 55ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (10987): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (10987):  
,I/SELinux (10987): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (10987):  
I/SELinux (10987):  
,I/SELinux (10987): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (10987): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(10987): >>>>> Normal User
,E/dalvikvm(10987): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (10987): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(10987): in addTimaSignatureService
,D/TimaKeyStoreProvider(10987): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(10987): Added TimaKesytore provider
,D/dalvikvm(10987): GC_CONCURRENT freed 3006K, 32% free 9557K/13948K, paused 3ms+2ms, total 29ms
,D/dalvikvm(10987): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/@ WidgetProvider(10987): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(10987): onUpdate called for widgetId : 0
,D/@ WidgetProvider(10987): Widget random data : 0
,D/@ WidgetProvider(10987): onUpdate called for widgetId : 5
,D/@ WidgetProvider(10987): Widget random data : 1
E/dalvikvm(10987): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(10987): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(10987): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(10987): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(10987): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(10987): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(10987): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(10987): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(10987): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(10987): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(10987): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(10987): VFY: replacing opcode 0x22 at 0x0038
I/ActivityManager( 2419): Killing 6286:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/dalvikvm(10987): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(10987): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(10987): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(10987): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SELinux (11016): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11016):  
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux (11016): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11016):  
I/SELinux (11016):  
,I/SELinux (11016): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11016): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm(11016): >>>>> Normal User
,E/dalvikvm(11016): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux (11016): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider(11016): in addTimaSignatureService
,D/TimaKeyStoreProvider(11016): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11016): Added TimaKesytore provider
,I/System.out(10987): Thread-627(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10987): Thread-627(ApacheHTTPLog):isShipBuild true
,I/System.out(10987): Thread-627(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm(11016): GC_CONCURRENT freed 2999K, 32% free 9571K/13952K, paused 4ms+2ms, total 30ms
,D/dalvikvm(11016): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/System.out(10987): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(10987): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(10987): Max ALLOWED memory (MB): 128
V/ImageManager(10987): Max SHOULD USE memory (MB): 128
,V/ImageManager(10987): Max Image Cache memory (MB): 32
,E/dalvikvm(11016): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm(11016): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm(11016): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm(11016): Unable to resolve superclass of Lal; (749)
W/dalvikvm(11016): Link of class 'Lal;' failed
E/dalvikvm(11016): Could not find class 'al', referenced from method b.a
W/dalvikvm(11016): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm(11016): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm(11016): Unable to resolve superclass of Lan; (749)
W/dalvikvm(11016): Link of class 'Lan;' failed
E/dalvikvm(11016): Could not find class 'an', referenced from method b.a
W/dalvikvm(11016): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm(11016): VFY: replacing opcode 0x22 at 0x002a
,I/dalvikvm(11016): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm(11016): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm(11016): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm(11016): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm(11016): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm(11016): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm(11016): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm(11016): VFY: replacing opcode 0x23 at 0x0005
,I/System.out(10987): AsyncNetworking-1-thread-1 calls detatch()
,D/dalvikvm(11016): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm(11016): Unable to resolve superclass of Lal; (749)
W/dalvikvm(11016): Link of class 'Lal;' failed
D/dalvikvm(11016): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
,W/dalvikvm(11016): Unable to resolve superclass of Lan; (749)
W/dalvikvm(11016): Link of class 'Lan;' failed
,D/dalvikvm(11016): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm(11016): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,D/skia    (10987): getTotalSize : Do not get file length
,D/@ WidgetProvider(10987): Building widget : 5
,I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
,W/dalvikvm(11016): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x000d
,D/ConnectivityService( 2419): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2577): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2577): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2577): updateDataNetType()
,D/STATUSBAR-NetworkController( 2577): NoService, mRoamingIconId = 0
,D/dalvikvm(11016): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(11016): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(11016): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm(11016): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm(11016): VFY: unable to resolve instance field 36
,D/dalvikvm(11016): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm(11016): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(11016): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(11016): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm(11016): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm(11016): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm(11016): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42353e90
D/dalvikvm(11016): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42353e90
,D/dalvikvm(11016): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42353e90, skipping init
,D/dalvikvm(11016): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42353e90
D/dalvikvm(11016): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42353e90
,V/JNIHelp (11016): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 2768): GC_CONCURRENT freed 8581K, 39% free 18643K/30384K, paused 10ms+8ms, total 108ms
,D/dalvikvm( 2768): WAIT_FOR_CONCURRENT_GC blocked 92ms
,I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm(11016): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(11016): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42353e90
,D/dalvikvm(11016): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42353e90
D/dalvikvm(11016): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42353e90
,D/dalvikvm(11016): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42353e90
,I/dalvikvm(11016): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm(11016): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm(11016): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm(11016): DexOpt: --- BEGIN 'ads2107266205.jar' (bootstrap=0) ---
,D/dalvikvm(11054): DexOpt: load 5ms, verify+opt 14ms, 194052 bytes
,I/ProviderInstaller(11016): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(11016): DexOpt: --- END 'ads2107266205.jar' (success) ---
,D/dalvikvm(11016): DEX prep '/data/data/com.google.android.youtube/cache/ads2107266205.jar': unzip in 0ms, rewrite 113ms
,E/YouTube MDX(11016): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm(11016): GC_CONCURRENT freed 1940K, 24% free 10704K/14024K, paused 6ms+5ms, total 52ms
,D/dalvikvm(11016): WAIT_FOR_CONCURRENT_GC blocked 19ms
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(11016): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(11016): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(11016): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(11016): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm(11016): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm(11016): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm(11016): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm(11016): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11016): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm(11016): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
D/dalvikvm(11016): VFY: replacing opcode 0x6e at 0x0002
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl(11016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl(11016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl(11016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc(11016): Found 10012
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/ActivityManager( 2419): Killing 6325:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/System.out(11016): Thread-692(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11016): Thread-692(ApacheHTTPLog):isShipBuild true
,I/System.out(11016): Thread-692(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(11016): Thread-692 calls detatch()
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/dalvikvm(11016): GC_CONCURRENT freed 1366K, 20% free 11317K/14104K, paused 6ms+6ms, total 51ms
,I/System.out(11016): Thread-675 calls detatch()
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/ActivityManager( 2419): Killing 6184:com.google.android.music:main/u0a125 (adj 15): empty for 1809s
,I/ActivityManager( 2419): Killing 6149:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1809s
,I/ActivityManager( 2419): Killing 6309:com.android.providers.calendar/u0a45 (adj 15): empty for 1809s
,I/ActivityManager( 2419): Killing 5971:com.android.calendar/u0a144 (adj 15): empty for 1809s
,I/ActivityManager( 2419): Killing 6313:com.sec.providers.settingsearch/u0a162 (adj 15): empty for 1810s
,I/ActivityManager( 2419): Killing 6268:com.sec.phone/1001 (adj 15): empty for 1811s
,I/ActivityManager( 2419): Killing 5387:com.google.android.talk/u0a109 (adj 15): empty for 1811s
,I/ActivityManager( 2419): Killing 5738:com.sec.android.diagmonagent/1000 (adj 15): empty for 1811s
,I/ActivityManager( 2419): Killing 5581:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1811s
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3744K, 74% free 24912K/95040K, paused 21ms+21ms, total 249ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) com.google.android.gms : 900(900)
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2577): handleTimeUpdate
,V/AlarmManager( 2419): (AppSync) ### 1 added ###
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2577): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2577): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2577):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2577): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2577): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 65
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
