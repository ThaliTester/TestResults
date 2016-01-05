#### Test 550731521dbc378_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 6659): GC_CONCURRENT freed 2993K, 28% free 9569K/13284K, paused 2ms+1ms, total 17ms
D/dalvikvm( 6659): WAIT_FOR_CONCURRENT_GC blocked 14ms
W/System.err( 6659): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 6659): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6659): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6659): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 6659): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 6659): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6659): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6659): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6659): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6659): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6659): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6659): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6659): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6659): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6659): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6659): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6659): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 6659): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6659): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6659): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6659): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6659): 	... 21 more
D/GalaxyFinderApplication( 6659): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 6659): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 6677): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6677):  
--------- beginning of /dev/log/system
I/ActivityManager( 2422): Killing 5960:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
I/SELinux ( 6677): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6677):  
I/SELinux ( 6677):  
I/SELinux ( 6677): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6677): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6677): >>>>> Normal User
E/dalvikvm( 6677): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 6677): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6677): in addTimaSignatureService
D/TimaKeyStoreProvider( 6677): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6677): Added TimaKesytore provider
D/dalvikvm( 6677): GC_CONCURRENT freed 3002K, 29% free 9565K/13292K, paused 3ms+1ms, total 18ms
D/dalvikvm( 6677): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/SELinux ( 6693): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6693):  
I/ActivityManager( 2422): Killing 5299:com.android.email/u0a157 (adj 15): empty #43
I/SELinux ( 6693): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6693):  
I/SELinux ( 6693):  
I/SELinux ( 6693): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6693): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6693): >>>>> Normal User
E/dalvikvm( 6693): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6693): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6693): in addTimaSignatureService
D/TimaKeyStoreProvider( 6693): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6693): Added TimaKesytore provider
D/dalvikvm( 6677): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42549ad8, skipping init
D/dalvikvm( 6693): GC_CONCURRENT freed 2994K, 28% free 9569K/13288K, paused 3ms+1ms, total 20ms
D/dalvikvm( 6693): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/SecureStorage( 6677): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1962): [INFO]: SPID(0x00000006)Credentials: uid 1000, gid 1000, pid 6677
I/SecureStorage( 1962): [INFO]: SPID(0x00000006)Received function mask & code: 00000106
,D/ActivityThread( 6693): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6693): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ActivityManager( 2422): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6693): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
I/SA      ( 5869): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5869): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5869): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5763): loadAuthorityPref(): sEnableAuthority = true
W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
D/AndroidRuntime( 6709): 
D/AndroidRuntime( 6709): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6709): CheckJNI is OFF
D/AndroidRuntime( 6709): setted country_code = Poland
D/AndroidRuntime( 6709): setted countryiso_code = PL
D/AndroidRuntime( 6709): setted sales_code = PLS
D/AndroidRuntime( 6709): readGMSProperty: start
D/AndroidRuntime( 6709): readGMSProperty: already setted!!
D/AndroidRuntime( 6709): readGMSProperty: end
D/AndroidRuntime( 6709): addProductProperty: start
I/SELinux ( 6721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6721):  
I/Icing.InternalIcingCorporaProvider( 6487): Updating corpora: A: com.test.thalitest, C: MAYBE
D/dalvikvm( 6709): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6709): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6709): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6709): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6709): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 8% free 9502K/10268K, paused 3ms+2ms, total 35ms
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 8% free 9502K/10268K, paused 2ms+2ms, total 24ms
I/SELinux ( 6721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6721):  
I/SELinux ( 6721):  
I/SELinux ( 6721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6721): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6721): >>>>> Normal User
E/dalvikvm( 6721): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6721): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 8% free 9502K/10268K, paused 1ms+3ms, total 25ms
D/TimaKeyStoreProvider( 6721): in addTimaSignatureService
D/TimaKeyStoreProvider( 6721): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6721): Added TimaKesytore provider
E/memtrack( 6709): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6709): failed to load memtrack module: -2
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/dalvikvm( 6709): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 6721): GC_CONCURRENT freed 2998K, 28% free 9572K/13292K, paused 4ms+1ms, total 44ms
D/dalvikvm( 6721): WAIT_FOR_CONCURRENT_GC blocked 35ms
D/CapabilityManagerService New( 6721): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 6741): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6741):  
I/ActivityManager( 2422): Killing 5389:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
D/AndroidRuntime( 6709): Calling main entry com.android.commands.am.Am
I/SELinux ( 6741): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6741):  
I/SELinux ( 6741):  
I/SELinux ( 6741): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6741): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6741): >>>>> Normal User
E/dalvikvm( 6741): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6741): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6741): in addTimaSignatureService
D/TimaKeyStoreProvider( 6741): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6741): Added TimaKesytore provider
V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SecureStorage( 1962): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1962): [INFO]: SPID(0x00000006)PID: 6677, TID: 6689
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
I/SELinux ( 6755): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6755):  
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6709): Shutting down VM
D/dalvikvm( 6709): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6755): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6755):  
I/SELinux ( 6755):  
I/SELinux ( 6755): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6755): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6755): >>>>> Normal User
E/dalvikvm( 6755): >>>>> com.test.thalitest [ userId:0 | appId:10584 ]
E/SELinux ( 6755): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm( 6741): GC_CONCURRENT freed 3008K, 29% free 9566K/13292K, paused 4ms+4ms, total 67ms
D/dalvikvm( 6741): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/TimaKeyStoreProvider( 6755): in addTimaSignatureService
D/PackageIntentReceiver( 6741): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6741): Not GearManger package! 
D/TimaKeyStoreProvider( 6755): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6755): Added TimaKesytore provider
I/Icing.InternalIcingCorporaProvider( 6487): UpdateCorporaTask done [took 551 ms] updated apps [took 551 ms] 
I/SELinux ( 6768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6768):  
I/ActivityManager( 2422): Killing 5824:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
I/ActivityManager( 2422): Killing 5637:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SQLiteSecureOpenHelper( 4173): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4173): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SELinux ( 6768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6768):  
I/SELinux ( 6768):  
I/SELinux ( 6768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6768): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6768): >>>>> Normal User
E/dalvikvm( 6768): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6768): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 6768): in addTimaSignatureService
D/TimaKeyStoreProvider( 6768): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6768): Added TimaKesytore provider
D/dalvikvm( 6755): GC_CONCURRENT freed 2994K, 28% free 9565K/13284K, paused 2ms+2ms, total 20ms
D/dalvikvm( 6755): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SecureStorage( 6677): [INFO]: SPID(0x00000000)Processing data has been completed
,D/dalvikvm( 6768): GC_CONCURRENT freed 2991K, 28% free 9574K/13288K, paused 4ms+1ms, total 23ms
,D/dalvikvm( 6768): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/MagazineService Version( 6768): Magazine-Channel: 13
,D/MagazineService Version( 6768): Magazine-Provider: 13
,D/MagazineService Version( 6768): Magazine-Administrator: 11
,V/WebViewChromium( 6755): Binding Chromium to the background looper Looper (main, tid 1) {4254d368}
,D/HeadlinesChannelApplication( 6768): [onCreate]
,I/chromium( 6755): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/MagazineService::MagazineBroadcastReceiver( 6768): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/BrowserProcessMain( 6755): Initializing chromium process, renderers=0
,I/MagazineService::MagazineService( 6768): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 6782): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6782):  
,I/PowerManagerService( 2422): [PWL] Off : 75s ago
,I/PowerManagerService( 2422): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2422): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2422): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3282, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=279)
D/MagazineService::MagazineService( 6768): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager( 2422): Killing 6085:com.sec.android.service.health/u0a16 (adj 15): empty #43
,W/chromium( 6755): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SELinux ( 6782): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6782):  
I/SELinux ( 6782):  
,I/SELinux ( 6782): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6782): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6782): >>>>> Normal User
,E/dalvikvm( 6782): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 6782): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/libEGL  ( 6755): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6755): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6755): loaded /system/lib/egl/libGLESv2_mali.so
,D/TimaKeyStoreProvider( 6782): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6782): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6782): Added TimaKesytore provider
I/Mali    ( 6755): Mali API Version : 401
,I/Mali    ( 6755): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6755): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6755): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6755): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6755): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6755): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6755): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2584): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2422): tr p:6755,o:f
W/dalvikvm( 6755): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6755): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6755): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6755): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6755): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6755): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6755): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6755): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6755): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6755): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6755): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6755): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6755): CordovaWebView is running on device made by: samsung
,D/dalvikvm( 6782): GC_CONCURRENT freed 3000K, 29% free 9569K/13292K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 6782): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/StatusBarManagerService( 2422): semi p:6755,o:f
D/PhoneStatusBar( 2584): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6755): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6755): Enabling debug mode 0
,W/AwContents( 6755): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/AwContents( 6755): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 6755): showStatusIcon on inactive InputConnection
,I/SELinux ( 6822): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6822):  
,I/ActivityManager( 2422): Killing 5839:com.sec.android.soagent/u0a38 (adj 15): empty #43
,I/SELinux ( 6822): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6822):  
I/SELinux ( 6822):  
,I/SELinux ( 6822): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6822): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6822): >>>>> Normal User
,E/dalvikvm( 6822): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 6822): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6822): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6822): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6822): Added TimaKesytore provider
,D/dalvikvm( 6822): GC_CONCURRENT freed 2999K, 28% free 9573K/13292K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6822): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/KidsPlatformStub( 6822): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6838): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6838):  
I/ActivityManager( 2422): Killing 6171:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,I/SELinux ( 6838): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6838):  
I/SELinux ( 6838):  
,I/SELinux ( 6838): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6838): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6838): >>>>> Normal User
,E/dalvikvm( 6838): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6838): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6838): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6838): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6838): Added TimaKesytore provider
,D/JsMessageQueue( 6755): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6838): GC_CONCURRENT freed 2985K, 28% free 9579K/13288K, paused 4ms+1ms, total 22ms
,D/dalvikvm( 6838): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/SELinux ( 6850): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6850):  
,I/ActivityManager( 2422): Killing 5916:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
I/SELinux ( 6850): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6850):  
I/SELinux ( 6850):  
I/SELinux ( 6850): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6850): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6850): >>>>> Normal User
E/dalvikvm( 6850): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6850): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/Icing   ( 3282): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,D/TimaKeyStoreProvider( 6850): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6850): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6850): Added TimaKesytore provider
,D/dalvikvm( 6755): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42545878
,D/dalvikvm( 6850): GC_CONCURRENT freed 2989K, 28% free 9577K/13288K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 6850): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 6755): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42545878
,D/jxcore_app_log( 6755): JniHelper::setJavaVM(0x41b42220), pthread_self() = 2027694184
,D/JX-Cordova( 6755): jxcore cordova android initializing
,D/UMC:Core( 6850): onCreate(): 
,D/USER_AGENT( 6850): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/[SAMSUNG SMARCART NATIVE]( 6850): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6850): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/TZ_CCM_C_GetFunctionList: ( 6850): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6850): FINISHED: initialize rv:0
,D/dalvikvm( 6755): GC_CONCURRENT freed 1293K, 16% free 11346K/13356K, paused 3ms+3ms, total 44ms
,D/dalvikvm( 6755): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 6755): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,I/Icing   ( 3282): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/dalvikvm( 6850): GC_CONCURRENT freed 1883K, 20% free 10767K/13368K, paused 4ms+3ms, total 54ms
,D/dalvikvm( 6850): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/UMC:SecurityUtils( 6850): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6850): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6850): New Flow
I/        ( 2422): CCM JNI: In ccm_register_for_default_cert
,I/        ( 2422): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2422): &ctx = 0x7bd05618
I/TLC_TZ_CCM: ( 2422): creating new ccm context...
I/TLC_TZ_CCM: ( 2422): initializing ccm context...
I/TLC_TZ_CCM: ( 2422): root = 0, root_strlen = 1
,D/TimaService( 2422): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2422): TIMA: in getTimaVersion
I/TLC_TZ_CCM: ( 2422): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2422): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2422): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2422): root = 0, root_len = 1
I/TZ: client_server_communication( 2422): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2422): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2422): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2422): Client_Server_Open was called
I/TZ: client_server_communication( 2422): IClientServer::IClientServer()
I/TZ: client_server_communication( 2422): BpClientServer::BpClientServer()
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
I/TZ: client_server_communication( 2422): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2422): ctx = 0x85c13ca8, comm = 0x85be3308, sendmsg = 0x85c90008, recvmsg = 0x85c94c08
,I/TZ_init: ( 2422): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
E/Parcel  ( 2422): nm 19456
E/TZ_init: ( 2422): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2422): trustlet initialization failed
,I/TZ_init: ( 2422): TZ_init_START...
,I/TZ_init: ( 2422): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2422): nm 19456
I/TZ_init: ( 2422): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2422): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
E/Parcel  ( 2422): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2422): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: ( 2422): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
E/Parcel  ( 2422): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2422): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2422): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2422): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
E/Parcel  ( 2422): nm 19456
I/TZ: client_server_communication( 2422): Client_Server_Close was called
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2511): tlc_close() was called
,I/TZ: mc_tlc_communication( 2511): Closing the session
I/TZ: mc_tlc_communication( 2511): Free WSM
,I/TZ: mc_tlc_communication( 2511): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2511): tlc_close() succeeded
,I/TZ: client_server_communication( 2422): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6850): TIMA service call for password change success!!
,D/UMC:AdminManager( 6850): init - start
,D/UMC:AdminManager( 6850): loadAdmins
,D/UMC:AdminManager( 6850): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6850): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6850): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6850): init - end
,V/UMC:AlarmHandler( 6850): Enter loadList
,D/EnterpriseDeviceManagerService( 2422): Creating context as user 0
,D/SPPApp  ( 6850): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6850): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6865): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6865):  
I/ActivityManager( 2422): Killing 6190:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,I/SELinux ( 6865): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6865):  
I/SELinux ( 6865):  
,I/SELinux ( 6865): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6865): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6865): >>>>> Normal User
,E/dalvikvm( 6865): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6865): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6865): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6865): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6865): Added TimaKesytore provider
,D/dalvikvm( 6755): GC_CONCURRENT freed 1874K, 15% free 14972K/17580K, paused 2ms+3ms, total 61ms
,D/dalvikvm( 6755): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 6865): GC_CONCURRENT freed 3000K, 29% free 9569K/13292K, paused 4ms+5ms, total 32ms
,D/dalvikvm( 6865): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/ApplicationPromenada( 6865): Application OnCreate start
,D/ApplicationPromenada( 6865): Application OnCreate po on Create
D/CrashReporter( 6865): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42557350
D/CrashReporter( 6865): Swaping uncaught exception handler
,D/ApplicationPromenada( 6865): Application OnCreate App Loader start
,D/ApplicationPromenada( 6865): Application OnCreate App Loader finish
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/p2.ApplicationLoader( 6865): ############################## cached apps: 
D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,V/WebViewChromium( 6865): Binding Chromium to the background looper Looper (main, tid 1) {42553168}
,I/chromium( 6865): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6865): Initializing chromium process, renderers=0
,W/chromium( 6865): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6865): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6865): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6865): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6865): Mali API Version : 401
,I/Mali    ( 6865): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6865): Application OnCreate Finish
,I/ActivityManager( 2422): Killing 6207:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/PackageBroadcastService( 3282): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3282): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3282): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3282): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3282): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3282): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3282): Submit a task: k
,D/ChimeraCfgMgr( 3282): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3282): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3282): Processing package: com.test.thalitest
,D/GassUtils( 3282): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/Finsky  ( 3886): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/k       ( 3282): Found info for package com.test.thalitest in db.
,D/dalvikvm( 6755): GC_FOR_ALLOC freed 5470K, 29% free 16294K/22668K, paused 46ms, total 47ms
,D/dalvikvm( 6865): GC_CONCURRENT freed 1775K, 19% free 10818K/13308K, paused 3ms+5ms, total 44ms
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5932): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5932): Breath 72437 latestRequest time : 1451989142851 current time : 1451989215288
,I/VacuumService( 2738): Vacuum at: now=1451989215539 tag=VacuumService
,D/dalvikvm( 6865): GC_CONCURRENT freed 2412K, 24% free 10445K/13584K, paused 3ms+2ms, total 82ms
,D/dalvikvm( 6865): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/Icing   ( 3282): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/dalvikvm( 6755): GC_CONCURRENT freed 6670K, 30% free 17741K/25204K, paused 3ms+11ms, total 96ms
,D/dalvikvm( 6755): WAIT_FOR_CONCURRENT_GC blocked 72ms
,W/ResourceType( 6865): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,I/Icing   ( 3282): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,W/PackageManager( 6865): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6865): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6865): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6865): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6865): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6865): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6865): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6865): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6865): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6865): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6865): 	at java.lang.Thread.run(Thread.java:841)
,D/dalvikvm( 6755): GC_FOR_ALLOC freed 1494K, 31% free 17452K/25204K, paused 47ms, total 47ms
,I/dalvikvm-heap( 6755): Grow heap (frag case) to 21.283MB for 3713210-byte allocation
,D/dalvikvm( 2422): GC_EXPLICIT freed 25996K, 71% free 25541K/86792K, paused 9ms+25ms, total 325ms
,D/dalvikvm( 6755): GC_FOR_ALLOC freed <1K, 27% free 21078K/28832K, paused 45ms, total 45ms
,W/jxcore-log( 6755): Initializing JXcore engine
,W/jxcore-log( 6755): JXcore engine is ready
,W/jxcore-log( 6755): Starting JXcore engine
,I/PhenotypeConfigurator( 2738): Scheduling Phenotype for one-off execution 881 seconds from now (1451989216624)
,D/dalvikvm( 6865): GC_CONCURRENT freed 2001K, 23% free 10492K/13584K, paused 6ms+6ms, total 59ms
,D/dalvikvm( 6865): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/GetConfigurationSnapshotOperation( 2738): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2738): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2738): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2738): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2738): Using platform SSLCertificateSocketFactory
,W/jxcore-log( 6755): Platform android
W/jxcore-log( 6755): 
,W/jxcore-log( 6755): Process ARCH arm
W/jxcore-log( 6755): 
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2738): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2738): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2738): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 2850): GC_CONCURRENT freed 1893K, 20% free 10831K/13512K, paused 5ms+6ms, total 62ms
D/SSRMv2:SIOP( 2422): SIOP:: AP = 360, Delta = 20
,I/System.out( 2738): Thread-120(HTTPLog):isShipBuild true
,I/System.out( 2738): Thread-120(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/p2.ApplicationLoader( 6865): Process time: 3470
,D/p2.ApplicationLoader( 6865): ##############################  apps after loading: 
,D/dalvikvm( 2738): GC_CONCURRENT freed 1637K, 18% free 11824K/14252K, paused 8ms+5ms, total 69ms
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 290, prevStep = 4, currStep = 4
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/jxcore-log( 6755): JXcore Cordova bridge is ready!
I/jxcore-log( 6755): 
,W/jxcore-log( 6755): JXcore engine is started
I/chromium( 6755): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6755): Toggling radios to true
I/jxcore-log( 6755): 
D/BluetoothAdapter( 6755): enable(): BT is already enabled..!
I/WifiManager( 6755): packageName : com.test.thalitest
I/WifiManager( 6755): setWifiEnabled : true
I/WifiService( 2422): setWifiEnabled: true pid=6755, uid=10584
W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=6755, uid=10584 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): Failed getting userId using ActivityManagerNative
W/WifiService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6755, uid=10584 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2422): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2422): disconnect: pid=6755, uid=10584
I/jxcore-log( 6755): Radios toggled
I/jxcore-log( 6755): 
I/wpa_supplicant( 3978): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6755): Received device characteristics:
I/jxcore-log( 6755): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 6755): Bluetooth name: S5mini-1
I/jxcore-log( 6755): Device name: samsung-SM-G800F
I/jxcore-log( 6755): 
I/jxcore-log( 6755): Perf Test app loaded loaded
I/jxcore-log( 6755): 
I/wpa_supplicant( 3978): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
D/Tethering( 2422): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/jxcore-log( 6755): check test folder
I/jxcore-log( 6755): 
I/wpa_supplicant( 3978): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3978): First Scan Start
W/Settings( 2422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3978): Scan requested (ret=0) - scan timeout 30 seconds
I/WifiStateMachine( 2422): ignore requestNetworkTransitionWakelock airplane:true
I/jxcore-log( 6755): found test : ./testFindPeers.js
I/jxcore-log( 6755): 
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/ConnectivityService( 2422): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3978): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3978): Skip scan - already scanning
D/ConnectivityService( 2422): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2422): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2422): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2584): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2584): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2422): Attempting to switch to mobile
D/ConnectivityService( 2422): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-IconMerger( 2584): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 6924): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6924):  
V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
V/RouteController( 1916): RTNETLINK answers: No such file or directory
D/CommandListener( 1916): Clearing all IP addresses on wlan0
I/jxcore-log( 6755): found test : ./testSendData.js
I/jxcore-log( 6755): 
I/SELinux ( 6924): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6924):  
I/SELinux ( 6924):  
I/SELinux ( 6924): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
W/NetworkManagementService( 2422): route cmd failed: 
W/NetworkManagementService( 2422): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2422): '
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2422): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2422): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SELinux ( 6924): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6924): >>>>> Normal User
E/dalvikvm( 6924): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
E/SELinux ( 6924): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/WifiStateMachine( 2422): Error! unhandled message{ when=-77ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2422): Error! unhandled message{ when=-75ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2422): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/TimaKeyStoreProvider( 6924): in addTimaSignatureService
V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
D/TimaKeyStoreProvider( 6924): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6924): Added TimaKesytore provider
D/NetUtils( 2422): android_net_utils_resetConnections in env=0x78d4d258 clazz=0x62100001 iface=wlan0 mask=0x3
D/ConnectivityService( 2422): resetConnections(wlan0, 3)
V/NativeCrypto( 2850): Read error: ssl=0x7b9c6cb0: I/O error during system call, Connection timed out
D/dalvikvm( 6924): GC_CONCURRENT freed 2990K, 28% free 9579K/13288K, paused 3ms+1ms, total 23ms
D/dalvikvm( 6924): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/System.out( 6924): Inside WakeupProvider
I/System.out( 6924): Inside onCreate() of WakeupTriggerProvide
V/NetworkStats( 2422): updateIfacesLocked()
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
I/VlingoApplication( 6924): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 6924): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/VlingoApplication( 6924): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
E/SPPClientService( 5599): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7b9c6cb0: I/O error during system call, Broken pipe
E/SPPClientService( 5599): [e] exceptionCaught(). NET_TIMEOUT
E/SPPClientService( 5599): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 37ms
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
I/chromium( 6755): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService( 2422): handleInetConditionChange: no active default network - ignore
E/SPPClientService( 5599): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5599): [b] ResponseMap empty
D/NearbySettings( 4752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 4752): DMSUtil.isNetworkConnected - flag-null, state-null
D/DialogFlow( 6924): initQueue()
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4752): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 4752): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2422): Killing 5377:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
D/NearbySettings( 4752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 4752): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4752): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 4752): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2422): updateDataUsageMap
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2584): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2584): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2584): updateDataNetType()
D/STATUSBAR-NetworkController( 2584): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6647): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6647): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6647): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6647): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4781): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6647): noConnectivity : true
,I/SELinux ( 6953): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6953):  
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...,
,I/SELinux ( 6953): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6953):  
I/SELinux ( 6953):  
,I/SELinux ( 6953): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6953): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6953): >>>>> Normal User
,E/dalvikvm( 6953): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ],
,E/SELinux ( 6953): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 6953): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6953): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6953): Added TimaKesytore provider
,D/dalvikvm( 6953): GC_CONCURRENT freed 3001K, 28% free 9567K/13288K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 6953): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/ActivityManager( 2422): Killing 6235:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,I/wpa_supplicant( 3978): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 3978): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3978): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/SELinux ( 6967): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6967):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 8% free 9502K/10268K, paused 2ms+3ms, total 27ms
,I/SELinux ( 6967): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6967):  
I/SELinux ( 6967):  
,I/SELinux ( 6967): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6967): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6967): >>>>> Normal User
,E/dalvikvm( 6967): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 6967): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): Associated with C0.AA.48
D/TimaKeyStoreProvider( 6967): in addTimaSignatureService
I/wpa_supplicant( 3978): freq(2412) increment count 2
,I/wpa_supplicant( 3978): meet head of list.
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 8% free 9502K/10268K, paused 4ms+4ms, total 38ms
,D/TimaKeyStoreProvider( 6967): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6967): Added TimaKesytore provider
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3978): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3978): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3978): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 8% free 9502K/10268K, paused 2ms+4ms, total 31ms
,D/WifiNative( 2422): callSECApiVoid - ID [50]
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 6967): GC_CONCURRENT freed 2998K, 28% free 9572K/13292K, paused 10ms+1ms, total 30ms
,D/dalvikvm( 6967): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,I/ActivityManager( 2422): Killing 6304:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/SELinux ( 6979): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6979):  
,I/SELinux ( 6979): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6979):  
I/SELinux ( 6979):  
,I/SELinux ( 6979): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6979): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6979): >>>>> Normal User
,E/dalvikvm( 6979): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6979): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6979): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6979): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6979): Added TimaKesytore provider
,D/dalvikvm( 6979): GC_CONCURRENT freed 3025K, 29% free 9548K/13292K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 6979): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/KLMS-2.3.201 : ( 6979): KLMSValidator() : checkQATesting()
,D/PackageManager( 2422): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/KLMS-2.3.201 : ( 6979): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451989221694
,I/KLMS-2.3.201 : ( 6979): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2422): Killing 6357:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 6997): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6997):  
,I/dhcpcd  ( 6991): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6991): bssid match
,I/SELinux ( 6997): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6997):  
I/SELinux ( 6997):  
,I/SELinux ( 6997): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6997): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6997): >>>>> Normal User
,E/dalvikvm( 6997): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 6997): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6997): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6997): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6997): Added TimaKesytore provider
,D/dalvikvm( 6997): GC_CONCURRENT freed 3004K, 29% free 9555K/13284K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 6997): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/SO_AGENT( 6997): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 6997): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5869): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5869): [BDLM] already registered in spp
I/SA      ( 5869): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5869): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5869): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5869): [OR] == isSIMCardReady false ==
I/SA      ( 5869): [SCU] == networkStateCheck == false
,I/SA      ( 5869): [OR] onReceive END
I/ActivityManager( 2422): Killing 6372:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7010): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7010):  
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7010): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7010):  
I/SELinux ( 7010):  
,I/SELinux ( 7010): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7010): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7010): >>>>> Normal User
,E/dalvikvm( 7010): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7010): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7010): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7010): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7010): Added TimaKesytore provider
,D/dalvikvm( 7010): GC_CONCURRENT freed 2998K, 28% free 9570K/13292K, paused 9ms+2ms, total 28ms
,D/dalvikvm( 7010): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/sCloudBackupApp( 7010): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7010): Other Intent
I/ActivityManager( 2422): Killing 6447:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7023): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7023):  
,I/SELinux ( 7023): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7023):  
I/SELinux ( 7023):  
,I/SELinux ( 7023): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7023): >>>>> Normal User
,E/dalvikvm( 7023): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7023): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7023): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7023): Added TimaKesytore provider
,D/dalvikvm( 7023): GC_CONCURRENT freed 2995K, 28% free 9577K/13292K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7023): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7023): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7023): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5401): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7023): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5401): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7023): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5401): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2422): Killing 5652:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5932): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5932): getCountryCode(): countryCode = PL
D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5932): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5932): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5932): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5932): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5932): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5932): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7035): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7035):  
,I/SELinux ( 7035): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7035):  
I/SELinux ( 7035):  
,I/SELinux ( 7035): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7035): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7035): >>>>> Normal User
,E/dalvikvm( 7035): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7035): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7035): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7035): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7035): Added TimaKesytore provider,
,D/dalvikvm( 7035): GC_CONCURRENT freed 2999K, 28% free 9571K/13288K, paused 4ms+2ms, total 24ms,
,D/dalvikvm( 7035): WAIT_FOR_CONCURRENT_GC blocked 18ms,
,V/WebViewChromium( 7035): Binding Chromium to the background looper Looper (main, tid 1) {42550148},
,I/chromium( 7035): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7035): Initializing chromium process, renderers=0
,W/chromium( 7035): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7035): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7035): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7035): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7035): Mali API Version : 401
,I/Mali    ( 7035): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7035): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7035): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/NSApplication( 7035): Starting up...
,I/iu.Environment( 6001): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 6001): SYNC; picasa accounts
,I/ActivityManager( 2422): Killing 6338:com.sec.phone/1001 (adj 15): empty #43
,I/iu.UploadsManager( 6001): num queued entries: 0
,D/QuickConnect[1.1][2] ( 5203): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5203): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5203): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4255e030
,I/iu.UploadsManager( 6001): num updated entries: 0,
,I/SELinux ( 7074): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7074):  
,I/iu.SyncManager( 6001): NEXT; no task,
,I/SELinux ( 7074): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
,I/SELinux ( 7074):  
I/SELinux ( 7074):  
I/SELinux ( 7074): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7074): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7074): >>>>> Normal User
,E/dalvikvm( 7074): >>>>> com.android.email [ userId:0 | appId:10157 ],
,E/SELinux ( 7074): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7074): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7074): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7074): Added TimaKesytore provider
,D/dalvikvm( 7074): GC_CONCURRENT freed 2985K, 28% free 9581K/13284K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7074): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/SELinux ( 7114): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7114):  
,W/ActivityManager( 2422): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2422): VerifyingLinkState enter
,I/SELinux ( 7114): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7114):  
I/SELinux ( 7114):  
,I/SELinux ( 7114): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7114): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7114): >>>>> Normal User
,E/dalvikvm( 7114): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7114): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/WifiStateMachine( 2422): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2422): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2422): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2422): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 2422): Killing 4926:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7114): in addTimaSignatureService
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2422): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2422): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2422): net.tcp.delack.wifi not found in system properties. Using defaults
,D/TimaKeyStoreProvider( 7114): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7114): Added TimaKesytore provider
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2584): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2584): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,I/ActivityManager( 2422): Killing 6503:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
D/PackageManager( 2422): [MSG] SEND_PENDING_BROADCAST
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@4326c9a8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
,I/SELinux ( 7140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7140):  
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,V/NetworkStats( 2422): updateIfacesLocked()
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked(flags=0x1)
I/SELinux ( 7140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7140):  
I/SELinux ( 7140):  
I/SELinux ( 7140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7140): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7140): >>>>> Normal User
E/dalvikvm( 7140): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
E/SELinux ( 7140): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/TimaKeyStoreProvider( 7140): in addTimaSignatureService
,D/RegisteredServicesCache( 2758): empty dynamic service
,D/TimaKeyStoreProvider( 7140): Cannot add TimaSignature Service, License check Failed
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
,D/ActivityThread( 7140): Added TimaKesytore provider
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,V/NetworkStats( 2422): performPollLocked() took 81ms
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
D/dalvikvm( 7114): GC_CONCURRENT freed 3006K, 29% free 9565K/13292K, paused 9ms+1ms, total 154ms
,D/dalvikvm( 7114): WAIT_FOR_CONCURRENT_GC blocked 145ms
,I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BadgeProvider( 7114): onCreate
,D/BadgeProvider( 7114): DatabaseHelper,
D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto",
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BadgeProvider( 7114): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,D/BadgeProvider( 7114): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 7114): sendNotify, [notify] : null
D/Launcher.Model( 2787): reloadBadges entered.
,D/BadgeProvider( 7114): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7114): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7114): update, [UpdateCount] : 1,
,D/dalvikvm( 7140): GC_CONCURRENT freed 3010K, 29% free 9559K/13288K, paused 32ms+1ms, total 99ms,
,D/dalvikvm( 7140): WAIT_FOR_CONCURRENT_GC blocked 64ms,
,D/STATUSBAR-NetworkController( 2584): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION,
D/STATUSBAR-NetworkController( 2584): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2584): updateDataNetType()
,D/STATUSBAR-NetworkController( 2584): NoService, mRoamingIconId = 0,
,I/DBG_DM  ( 4781): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected,
,D/hcjo    ( 6023): AutoUpdateManager:IDLE:execute,
,D/InitializeManagerStateMachine( 6023): execute::IDLE:EXECUTE,
D/InitializeManagerStateMachine( 6023): exit::IDLE
,D/InitializeManagerStateMachine( 6023): entry::NETWORK_CHECK,
D/InitializeManagerStateMachine( 6023): execute::NETWORK_CHECK:NETWORK_STATE_OK,
,D/InitializeManagerStateMachine( 6023): exit::NETWORK_CHECK,
D/InitializeManagerStateMachine( 6023): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6023): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK,
,D/InitializeManagerStateMachine( 6023): exit::CHECK_COUNTRY_INFO,
D/InitializeManagerStateMachine( 6023): entry::SUCCESS
,D/hcjo    ( 6023): AutoUpdateManager:INITCHECK:onInitializeSuccess,
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/hcjo    ( 6023): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/hcjo    ( 6023): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2422): MasterInitialState.processMessage what=3
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,I/HarmonyEASService( 2422): Updating for all 1,
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
D/CaptivePortalTracker( 2422): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/InitializeManagerStateMachine( 6023): exit::SUCCESS
,D/InitializeManagerStateMachine( 6023): entry::IDLE,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SPPClientService( 5599): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5599): [SystemStateMoniter] Current Time : 156720
,E/SPPClientService( 5599): [SystemStateMoniter] No Connect : true
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/SPPClientService( 5599): [[SystemStateMonitorService]] No Active Internet
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 4752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4752): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4752): MountReceiver.onReceive - Keep current state
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 4752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4752): MountReceiver.onReceive - Keep current state
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5599): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5599): [a] [ConnectionManager] Connection is already disconnected.
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 4752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/NearbySettings( 4752): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4752): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4752): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5599): [[PushClientService]] <<--- deInitPushClientService  END  --->>
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2422): Killing 6406:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SPPClientService( 5599): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/NearbySettings( 4752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4752): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422
,I/Icing.InternalIcingCorporaProvider( 6487): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,E/SPPClientService( 5599): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SELinux ( 7162): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7162):  
,E/SPPClientService( 5599): [a] [ConnectionManager] Connection is already disconnected.
W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2422): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2422):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2422): updateSourceRoutes : no source routing conditions
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
,E/SPPClientService( 5599): [g] getNetMCC return empty string
,I/SELinux ( 7162): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7162):  
I/SELinux ( 7162):  
,I/SELinux ( 7162): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7162): >>>>> Normal User
,E/dalvikvm( 7162): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
,E/SELinux ( 7162): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7162): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7162): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7162): Added TimaKesytore provider
,I/Icing.InternalIcingCorporaProvider( 6487): UpdateCorporaTask done [took 147 ms] updated apps [took 147 ms] 
,D/dalvikvm( 7162): GC_CONCURRENT freed 2997K, 28% free 9566K/13284K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7162): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/FileShare-Server( 7162): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/SELinux ( 7174): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7174):  
,I/SELinux ( 7174): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7174):  
I/SELinux ( 7174):  
,I/SELinux ( 7174): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7174): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7174): >>>>> Normal User
,E/dalvikvm( 7174): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ],
,E/SELinux ( 7174): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7174): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7174): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7174): Added TimaKesytore provider,
,D/dalvikvm( 2422): GC_EXPLICIT freed 3756K, 71% free 25631K/86792K, paused 15ms+27ms, total 314ms,
,I/dalvikvm( 6755): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported,
W/dalvikvm( 6755): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6755): VFY: replacing opcode 0x6e at 0x0002,
D/AndroidRuntime( 6755): Shutting down VM
,W/dalvikvm( 6755): threadid=1: thread exiting with uncaught exception (group=0x41b55c08),
E/AndroidRuntime( 6755): FATAL EXCEPTION: main
E/AndroidRuntime( 6755): Process: com.test.thalitest, PID: 6755
E/AndroidRuntime( 6755): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6755): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121),
E/AndroidRuntime( 6755): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 6755): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 6755): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 6755): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 6755): ,	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 6755): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6755): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6755): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6755): 	at android.os.Handler.handleCallback(Handler.java:733),
E/AndroidRuntime( 6755): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6755): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6755): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6755): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2422):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,D/dalvikvm( 7174): GC_CONCURRENT freed 3006K, 29% free 9565K/13292K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 7174): WAIT_FOR_CONCURRENT_GC blocked 27ms
I/ActivityManager( 2422): Killing 6052:com.android.calendar/u0a144 (adj 15): empty #43
,I/Process ( 6755): Sending signal. PID: 6755 SIG: 9
,D/CrashAnrDetector( 2422): processName: com.test.thalitest
,D/CrashAnrDetector( 2422): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.acquire()
,D/BezelQuickConnect( 5215): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5215): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
I/ActivityManager( 2422): Killing 6388:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/DBG_DM  ( 4781): [3.19.140541][Line:408][onResume] 
,D/PackageBroadcastService( 3282): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/11)
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/11)
I/WindowState( 2422): WIN DEATH: Window{4644b8b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 2422): Process com.test.thalitest (pid 6755) (adj 9) has died.
,I/DBG_DM  ( 4781): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
,I/DBG_DM  ( 4781): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/PCWCLIENTTRACE_PushUtil( 6647): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6647): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6647): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6647): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4781): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4781): [3.19.140541][Line:418][onResume] Postpone Count : 27
,I/DBG_DM  ( 4781): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4781): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4781): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(2) - 4
,I/DBG_DM  ( 4781): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
,I/DBG_DM  ( 4781): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4781): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4781): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4781): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4781): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4781): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4781): setTransGradationMode to true
,D/StatusBarManagerService( 2422): semi p:4781,o:t
D/PhoneStatusBar( 2584): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/DBG_DM  ( 4781): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1922): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.3.201 : ( 6979): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/InputMethodManagerService( 2422): Got RemoteException sending setActive(false) notification to pid 6755 uid 10584
,I/KLMS-2.3.201 : ( 6979): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451989225515
,I/KLMS-2.3.201 : ( 6979): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/SO_AGENT( 6997): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 6997): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7201): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7201):  
,I/GallerySearchProvider( 3594): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 8% free 9502K/10268K, paused 3ms+3ms, total 34ms
,I/SELinux ( 7201): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7201):  
I/SELinux ( 7201):  
,I/SELinux ( 7201): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7201): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7201): >>>>> Normal User
,E/dalvikvm( 7201): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/SELinux ( 7201): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 8% free 9502K/10268K, paused 3ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7201): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7201): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7201): Added TimaKesytore provider
,I/System.out( 6967): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6967): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 6967): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 8% free 9502K/10268K, paused 2ms+3ms, total 25ms
,I/SELinux ( 7214): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7214):  
,I/SA      ( 5869): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5869): [BDLM] already registered in spp
,I/SA      ( 5869): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5869): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5869): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5869): [OR] == isSIMCardReady false ==
,I/SA      ( 5869): [SCU] == networkStateCheck == true
I/SA      ( 5869): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5869): isChinaCountryCode : false
,I/SA      ( 5869): [OR] == networkStateCheck true ==
,I/SA      ( 5869): [OR] GetMyCountryZoneTask
,I/SA      ( 5869): [OR] onReceive END
,I/SA      ( 5869): [SRS] prepareGetMyCountryZone
,I/SA      ( 5869): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5869): [SSP] query invoked
,I/SELinux ( 7214): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7214):  
I/SELinux ( 7214):  
,I/SELinux ( 7214): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7214): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7214): >>>>> Normal User
,E/dalvikvm( 7214): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7214): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5869): [TPMU] GetMccFromDB : null
,I/SA      ( 5869): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5869): [TPM] isNoProxy(default) : true
,I/SA      ( 5869): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7010): Other Intent
,D/TimaKeyStoreProvider( 7214): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7214): Cannot add TimaSignature Service, License check Failed
D/com.samsung.app( 7023): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityThread( 7214): Added TimaKesytore provider
,D/com.samsung.app( 7023): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/dalvikvm( 7201): GC_CONCURRENT freed 2981K, 28% free 9583K/13288K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7201): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Headlines( 5932): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5932): getCountryCode(): countryCode = PL
D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5932): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5932): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5932): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5932): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5932): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5932): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 6967): AsyncTask #1 calls detatch()
,I/iu.Environment( 6001): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6001): num queued entries: 0
,I/iu.UploadsManager( 6001): num updated entries: 0
,I/iu.SyncManager( 6001): NEXT; no task
,D/QuickConnect[1.1][2] ( 5203): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
W/System.err( 6967): com.sec.android.fota.osp.http.RestClientException
W/System.err( 6967): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6967): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6967): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6967): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 6967): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 6967): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6967): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 6967): Caused by: java.lang.NullPointerException
,W/System.err( 6967): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 6967): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6967): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6967): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6967): 	... 8 more
I/QuickConnect[1.1][2] ( 5203): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5203): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4255e030
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
D/dalvikvm( 7214): GC_CONCURRENT freed 3003K, 28% free 9570K/13292K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 7214): WAIT_FOR_CONCURRENT_GC blocked 23ms
,V/KVNProvider( 7214): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7214): getFindoCursor query string : 
,D/hcjo    ( 6023): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6023): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6023): exit::IDLE
,D/InitializeManagerStateMachine( 6023): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6023): execute::NETWORK_CHECK:NETWORK_STATE_OK
,V/KVNProvider( 7214): getTagSearchCursor() tagSearchCursor count : 0
D/InitializeManagerStateMachine( 6023): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6023): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6023): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6023): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6023): entry::SUCCESS
,D/hcjo    ( 6023): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6023): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6023): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6023): exit::SUCCESS
,D/InitializeManagerStateMachine( 6023): entry::IDLE
,I/ActivityManager( 2422): Killing 6222:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5599): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5599): [SystemStateMoniter] Current Time : 158223
,E/SPPClientService( 5599): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5599): GC_CONCURRENT freed 1975K, 22% free 10438K/13272K, paused 3ms+3ms, total 34ms
,I/Icing   ( 3282): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3282): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/SA      ( 5869): [RC New] [v2liruge] api execute + 650
,I/SA      ( 5869): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5869): AsyncTask #2 calls detatch()
,I/SA      ( 5869): [TPMU] getNetworkMcc : 
,I/SA      ( 5869): [SCU] saveMccToPreferece Start
I/SA      ( 5869): [SCU] RegionMCC : 260
,I/SA      ( 5869): [SSP] query invoked
I/SA      ( 5869): [TPMU] GetMccFromDB : null
,I/SA      ( 5869): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5869): [SCU] saveMccToPreferece End
I/SA      ( 5869): [RC New] executeRequest [v2liruge] end. 674
I/SA      ( 5869): [RC New] Execute end
I/SA      ( 5869): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5869): [OR] GetMyCountryZoneTask Success
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/WifiStateMachine( 2422): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5599): [b] __InitReply__
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 360, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 7035): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2422): Killing 6257:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 160381
D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0)
D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3477)
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 3886): GC_CONCURRENT freed 7979K, 35% free 16339K/25036K, paused 11ms+7ms, total 139ms
,D/dalvikvm( 3886): WAIT_FOR_CONCURRENT_GC blocked 72ms
,D/Finsky  ( 3886): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3886): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6647): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6647): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6647): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6647): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6647): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6647): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6647): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6647): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6647): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5932): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5932): Breath 7075 latestRequest time : 1451989225808 current time : 1451989232883
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 6023): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6023): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6023): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6023): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6023): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6023): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6023): entry::IDLE
,D/CaptivePortalTracker( 2422): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2422): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2422): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2422): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2422): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2422): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6023): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6023): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6023): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6023): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6023): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6023): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6023): entry::IDLE,
,E/Watchdog( 2422): !@Sync 5,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = -30,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4,
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{447827e0 u0 com.sec.spp.push/.PushClientService},
,I/PowerManagerService( 2422): [PWL] Off : 105s ago,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate,
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2422): !@Sync 6,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5932): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5932): Breath 54874 latestRequest time : 1451989225808 current time : 1451989280682,
,I/SELinux ( 7484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7484):  
,I/SELinux ( 7484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7484):  
I/SELinux ( 7484):  
I/SELinux ( 7484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7484): >>>>> Normal User
,E/dalvikvm( 7484): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ],
,E/SELinux ( 7484): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
,D/TimaKeyStoreProvider( 7484): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7484): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7484): Added TimaKesytore provider,
,D/dalvikvm( 7484): GC_CONCURRENT freed 3004K, 29% free 9556K/13284K, paused 3ms+2ms, total 24ms,
,D/dalvikvm( 7484): WAIT_FOR_CONCURRENT_GC blocked 21ms,
,E/SPPClientService( 7484): ============PushLog. commonIsShipBuild. stop!,
,E/SPPClientService( 7484): [PushClientApplication] Push log off : This is Ship build version,
,D/SPPClientService( 7484): PushLog.txt file is not deleted.,
D/SPPClientService( 7484): PushLog.txt file is not deleted.
,D/SPPClientService( 7484): ============PushLog. stop!,
,E/SPPClientService( 5599): [b] __PingReply__
,I/ActivityManager( 2422): Killing 6588:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5932): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5932): Breath 67067 latestRequest time : 1451989225808 current time : 1451989292876,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate,
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 7,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5932): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5932): Breath 97069 latestRequest time : 1451989225808 current time : 1451989322877,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate,
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 8,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5932): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5932): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5932): Breath 127068 latestRequest time : 1451989225808 current time : 1451989352876,
,D/Headlines( 5932): stop ,
,D/Headlines( 5932): Breath.onDestroy : ,
I/ActivityManager( 2422): Killing 6508:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/Watchdog( 2422): !@Sync 9,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2422): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2422): initializing...,
I/TLC_TIMA_PKM_initialize( 2422): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2422): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2422): device_id = 0x0
I/TZ: mc_tlc_communication( 2422): tlc_open() was called
,I/TZ: mc_tlc_communication( 2422): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2422): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2422): Opening the session
,I/TZ: mc_tlc_communication( 2422): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2422): Trustlet response is completed,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 275s ago,
,E/Watchdog( 2422): !@Sync 11,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7816): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7816):  
,I/SELinux ( 7816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7816):  
I/SELinux ( 7816):  
,I/SELinux ( 7816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7816): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7816): >>>>> Normal User
,E/dalvikvm( 7816): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7816): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7816): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7816): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7816): Added TimaKesytore provider,
,D/dalvikvm( 7816): GC_CONCURRENT freed 3008K, 29% free 9555K/13284K, paused 2ms+2ms, total 26ms,
,D/dalvikvm( 7816): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/ActivityManager( 2422): Killing 6618:com.samsung.groupcast/u0a15 (adj 15): empty #43,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2422): !@Sync 12
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2422): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 13
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 4423K, 72% free 25150K/86792K, paused 22ms+22ms, total 261ms
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 14
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 15
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 16
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2422): [PWL] Off : 455s ago
,E/Watchdog( 2422): !@Sync 17
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 18
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 19
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 8466
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 8468
W/ProcessCpuTracker( 2422): Skipping unknown process pid 8469
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 8471
W/ProcessCpuTracker( 2422): Skipping unknown process pid 8473
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 8474
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 8480
,E/Watchdog( 2422): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 21
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService( 2422): [PWL] Off : 600s ago
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 15
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2584): GC_CONCURRENT freed 15746K, 33% free 33852K/50316K, paused 38ms+9ms, total 122ms
,I/GAV2    ( 5699): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5699): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2422): !@Sync 22
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 23
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 24
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 25
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4092): GC_CONCURRENT freed 2880K, 28% free 9725K/13324K, paused 9ms+2ms, total 67ms
,E/Watchdog( 2422): !@Sync 26
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 27
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_CONCURRENT freed 4091K, 72% free 24948K/86752K, paused 9ms+16ms, total 210ms
,E/Watchdog( 2422): !@Sync 28
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 29
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 31
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 32
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 33
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 34
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 6001): GC_CONCURRENT freed 527K, 5% free 26799K/28048K, paused 5ms+5ms, total 44ms
,D/dalvikvm( 6001): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 35
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 36
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5599): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,E/SPPClientService( 5599): [b] __PingReply__
,I/PowerManagerService( 2422): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 37
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 38
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 39
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 40
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 41
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 3745K, 72% free 24986K/86752K, paused 21ms+19ms, total 241ms
,V/AlarmManager( 2422): waitForAlarm result :4
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
,D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3282): Aggregate from 1451988516884 (log), 1451988516884 (data)
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 15
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3282): GC_CONCURRENT freed 2182K, 19% free 12649K/15548K, paused 5ms+11ms, total 108ms
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 42
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 43
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1265s ago
,E/Watchdog( 2422): !@Sync 44
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2422): stay LED for fully charged
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 45
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 46
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 47
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1380s ago
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 48
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 49
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4092): GC_CONCURRENT freed 2048K, 28% free 9722K/13324K, paused 3ms+2ms, total 41ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 50
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 51
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1500s ago,
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 52
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 53
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 54
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 55
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_FOR_ALLOC freed 3777K, 72% free 25083K/86752K, paused 187ms, total 187ms
,D/dalvikvm( 2422): GC_CONCURRENT freed 337K, 72% free 24790K/86752K, paused 9ms+16ms, total 197ms
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 56
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 57
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 58
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 59
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2422): Prepared write state in 49ms
,I/ProcessStatsService( 2422): Prepared write state in 38ms
,I/ProcessStatsService( 2422): Pruning old procstats: /data/system/procstats/state-2016-01-04-17-03-17.bin
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 60
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService( 2422): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 61
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 62
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 63
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2584): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 64
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1890s ago
,TIME-OUT KILL (timeout was 1800000ms)
```
