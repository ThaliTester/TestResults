#### Test 506502781a07ac8_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5211, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5211): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager(  761): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5211): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
I/SA      ( 4068): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4068): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4068): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4366): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2185): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5243):  
I/IcingCorporaProvider( 2185): UpdateCorporaTask done [took 82 ms] updated apps [took 81 ms] 
I/SELinux ( 5243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5243):  
I/SELinux ( 5243):  
I/SELinux ( 5243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5243): >>>>> Normal User
E/dalvikvm( 5243): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/ActivityManager(  761): Killing 3987:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/TimaKeyStoreProvider( 5243): in addTimaSignatureService
D/TimaKeyStoreProvider( 5243): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5243): Added TimaKesytore provider
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5243, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 5243): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 5256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5256):  
I/ActivityManager(  761): Killing 4300:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5256):  
I/SELinux ( 5256):  
I/SELinux ( 5256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5256): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5256): >>>>> Normal User
E/dalvikvm( 5256): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5256): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5256): in addTimaSignatureService
D/TimaKeyStoreProvider( 5256): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5256): Added TimaKesytore provider
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5256, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5280):  
I/SELinux ( 5280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5280):  
I/SELinux ( 5280):  
I/SELinux ( 5280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5280): >>>>> Normal User
E/dalvikvm( 5280): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  761): Killing 4009:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5256): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 5280): in addTimaSignatureService
D/TimaKeyStoreProvider( 5280): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5280): Added TimaKesytore provider
E/SMD     (  242): DCD ON
D/PackageIntentReceiver( 5280): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5280): Not GearManger package! 
I/SELinux ( 5309): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5309):  
I/SELinux ( 5309): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5309):  
I/SELinux ( 5309):  
I/SELinux ( 5309): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5309): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5309): >>>>> Normal User
E/dalvikvm( 5309): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5309): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5309): in addTimaSignatureService
D/TimaKeyStoreProvider( 5309): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5309): Added TimaKesytore provider
D/MagazineService Version( 5309): Magazine-Channel: 13
D/MagazineService Version( 5309): Magazine-Provider: 13
D/MagazineService Version( 5309): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5309): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5309): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5309, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5309): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5322):  
D/MagazineService::MagazineService( 5309): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  761): Killing 1334:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/AndroidRuntime( 5277): 
D/AndroidRuntime( 5277): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/GAV2    ( 5256): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/AndroidRuntime( 5277): CheckJNI is OFF
D/AndroidRuntime( 5277): setted country_code = Poland
D/AndroidRuntime( 5277): setted countryiso_code = PL
D/AndroidRuntime( 5277): setted sales_code = XEO
D/AndroidRuntime( 5277): readGMSProperty: start
D/AndroidRuntime( 5277): readGMSProperty: already setted!!
D/AndroidRuntime( 5277): readGMSProperty: end
D/AndroidRuntime( 5277): addProductProperty: start
I/ActivityManager(  761): Killing 4406:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5322):  
I/SELinux ( 5322):  
I/SELinux ( 5322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5322): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5322): >>>>> Normal User
E/dalvikvm( 5322): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
D/dalvikvm( 5277): Trying to load lib libjavacore.so 0x0
E/SELinux ( 5322): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 5277): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5277): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5277): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5277): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/TimaKeyStoreProvider( 5322): in addTimaSignatureService
D/TimaKeyStoreProvider( 5322): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5322): Added TimaKesytore provider
E/memtrack( 5277): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5277): failed to load memtrack module: -2
I/SELinux ( 5343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5343):  
I/ActivityManager(  761): Killing 4421:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
D/dalvikvm( 5277): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 5343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5343):  
I/SELinux ( 5343):  
I/SELinux ( 5343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5343): >>>>> Normal User
E/dalvikvm( 5343): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5343): in addTimaSignatureService
D/TimaKeyStoreProvider( 5343): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5343): Added TimaKesytore provider
D/AndroidRuntime( 5277): Calling main entry com.android.commands.am.Am
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5343, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5343): Package not found : com.sec.android.app.kidshome
I/SELinux ( 5357): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5357):  
I/ActivityManager(  761): Killing 4433:com.sec.esdk.elm/u0a94 (adj 15): empty #43
V/ApplicationPolicy(  761): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  761): mDVFSHelper.acquire()
I/SELinux ( 5357): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5357):  
I/SELinux ( 5357):  
I/SELinux ( 5357): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5357): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5357): >>>>> Normal User
E/dalvikvm( 5357): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5357): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 5367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5367):  
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 5277): Shutting down VM
D/dalvikvm( 5277): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
D/TimaKeyStoreProvider( 5357): in addTimaSignatureService
D/TimaKeyStoreProvider( 5357): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5357): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget visibility changed visibility = false on instance = 1
I/SELinux ( 5367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5367):  
I/SELinux ( 5367):  
I/SELinux ( 5367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5367): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5367): >>>>> Normal User
E/dalvikvm( 5367): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5367): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1249): destroyHardwareResources():1130400480
D/TimaKeyStoreProvider( 5367): in addTimaSignatureService
D/TimaKeyStoreProvider( 5367): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5367): Added TimaKesytore provider
D/LockPatternUtils( 1069): isPcwEnable = null
I/SurfaceFlinger(  248): id=8 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=8 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 2079): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2079): getDatabaseLocked(b,b,pwd)...
D/Launcher( 1249): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1249): destroyHardwareResources():1130400480
I/ActivityManager(  761): Killing 3582:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/Finsky  ( 3695): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5367, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraModuleLdr( 1781): Loading module APK com.google.android.play.games
I/dalvikvm( 1781): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1781): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0053
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5367, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5367): Binding Chromium to the background looper Looper (main, tid 1) {426df438}
I/chromium( 5367): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5367): Initializing chromium process, renderers=0
W/chromium( 5367): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5367): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5367): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5367): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5367): Remote Branch: 
I/Adreno-EGL( 5367): Local Patches: 
I/Adreno-EGL( 5367): Reconstruct Branch: 
,I/dalvikvm( 1781): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1781): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1781): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1781): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1781): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1781): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
I/dalvikvm( 5367): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5367): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5367): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5367): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5367): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5367): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5367): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5367): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5367): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5367): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5367): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5367): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5367): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5367): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5367): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5367): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5367): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5367): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5367): CordovaWebView is running on device made by: samsung
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
I/SurfaceFlinger(  248): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5367): EGLImpl-HWUI Protected EGL context created
D/AsyncTaskServiceImpl( 1781): Submit a task: k
D/OpenGLRenderer( 5367): Enabling debug mode 0
W/AwContents( 5367): nativeOnDraw failed; clearing to background color.
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  761): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/k       ( 1781): Processing package: com.test.thalitest
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
D/GassUtils( 1781): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
D/k       ( 1781): Found info for package com.test.thalitest in db.
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1781): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1781): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1781): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1781): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1781): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1781): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1781): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1781): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1781): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1781): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0006
I/PeopleDatabaseHelper( 1781): cleanUpNonGplusAccounts done.
D/JsMessageQueue( 5367): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5367): Trying to load lib /data/app-lib/com.test.thalitest-58/libjxcore.so 0x42a06170
,D/dalvikvm( 5367): Added shared lib /data/app-lib/com.test.thalitest-58/libjxcore.so 0x42a06170
D/jxcore_app_log( 5367): JniHelper::setJavaVM(0x41c2a4f8), pthread_self() = 2033118824
,D/JX-Cordova( 5367): jxcore cordova android initializing
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 1781): GC_CONCURRENT freed 1797K, 36% free 12256K/19056K, paused 4ms+4ms, total 53ms
,D/dalvikvm( 5367): GC_CONCURRENT freed 4923K, 33% free 12769K/19056K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 5367): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/AmoledAdjustTimer(  761): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@9
,D/dalvikvm( 5367): GC_FOR_ALLOC freed 4678K, 28% free 15744K/21808K, paused 31ms, total 31ms
,I/Icing   ( 1781): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1781): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 5367): GC_FOR_ALLOC freed 5059K, 32% free 16758K/24496K, paused 33ms, total 33ms
,I/dalvikvm-heap( 5367): Grow heap (frag case) to 22.056MB for 2475476-byte allocation
,E/SMD     (  242): DCD ON
,D/dalvikvm( 5367): GC_FOR_ALLOC freed 3779K, 36% free 17444K/26916K, paused 31ms, total 31ms
,D/dalvikvm( 5367): GC_FOR_ALLOC freed 1215K, 36% free 17344K/26916K, paused 29ms, total 29ms
,W/jxcore-log( 5367): Initializing JXcore engine
,W/jxcore-log( 5367): JXcore engine is ready
,W/jxcore-log( 5367): Starting JXcore engine
,W/jxcore-log( 5367): Platform android
W/jxcore-log( 5367): 
,W/jxcore-log( 5367): Process ARCH arm
W/jxcore-log( 5367): 
,I/jxcore-log( 5367): JXcore Cordova bridge is ready!
I/jxcore-log( 5367): 
,W/jxcore-log( 5367): JXcore engine is started
,I/chromium( 5367): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 67838 latestRequest time : 1450437968547 current time : 1450438036385
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GAV2    ( 5256): Thread[GAThread,5,main]: No campaign data found.
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/VacuumService( 1210): Vacuum at: now=1450438036539 tag=VacuumService
,D/FactoryTest( 4769): Not factory mode
,D/FactoryTest( 4769): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4769): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4769): still no open session command from host, so toast
,V/ApplicationPolicy(  761): isApplicationStateBlocked userId 0 pkgname com.android.settings
W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  761): mDVFSHelper.acquire()
,D/LockPatternUtils( 1069): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2079): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2079): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/MTPRx   ( 4769): started activity for popup
,E/SettingsReceiverActivity( 4769): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4769): dev.kiessupport is : TRUE
,D/dalvikvm(  761): GC_EXPLICIT freed 2707K, 58% free 23929K/56092K, paused 21ms+14ms, total 148ms
,I/SurfaceFlinger(  248): id=18 createSurf (1x1),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4769): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4769): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4769): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4769): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4769): Remote Branch: 
I/Adreno-EGL( 4769): Local Patches: 
I/Adreno-EGL( 4769): Reconstruct Branch: 
,I/HWUI    ( 4769): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4769): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  761): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5367): Toggling radios to true
I/jxcore-log( 5367): 
,D/BluetoothAdapter( 5367): enable(): BT is already enabled..!
,I/WifiManager( 5367): packageName : com.test.thalitest
,I/WifiManager( 5367): setWifiEnabled : true
,I/WifiService(  761): setWifiEnabled: true pid=5367, uid=10179
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5367, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  761): Failed getting userId using ActivityManagerNative
W/WifiService(  761): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5367, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  761): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  761): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  761): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  761): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  761): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  761): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  761): disconnect: pid=5367, uid=10179
,I/jxcore-log( 5367): Radios toggled
I/jxcore-log( 5367): 
,I/wpa_supplicant( 1961): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5367): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): Perf Test app loaded loaded
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): check test folder
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): found test : ./testFindPeers.js
I/jxcore-log( 5367): 
,I/wpa_supplicant( 1961): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1961): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  761): InitialState.processMessage what=4
E/wpa_supplicant( 1961): Cmd 35605 not handled
E/wpa_supplicant( 1961): Cmd 35605 not handled
E/Tethering(  761): No numeric data
,I/wpa_supplicant( 1961): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,I/jxcore-log( 5367): found test : ./testSendData.js
I/jxcore-log( 5367): 
V/NetworkStats(  761): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1961): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1961): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1961): First Scan Start
,I/wpa_supplicant( 1961): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  761): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  761): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService(  761): InactiveState{ what=143375 }
,D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,V/NetworkStats(  761): performPollLocked() took 74ms
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
D/ConnectivityService(  761): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  761): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  761): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
I/wpa_supplicant( 1961): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1961): Skip scan - already scanning
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/WifiP2pService(  761): InactiveState{ what=143375 }
D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
E/ConnectivityService(  761): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  761): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  761): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/ConnectivityService(  761): Attempting to switch to mobile
D/ConnectivityService(  761): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
V/RouteController(  239): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 5478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5478):  
V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -6 rule del table 2 2>&1
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  761): Error! unhandled message{ when=-84ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  761): Error! unhandled message{ when=-85ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  761): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 5478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5478):  
I/SELinux ( 5478):  
I/SELinux ( 5478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5478): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5478): >>>>> Normal User
E/dalvikvm( 5478): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
W/NetworkManagementService(  761): route cmd failed: 
W/NetworkManagementService(  761): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  761): '
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  761): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  761): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController(  239): /system/bin/ip -4 route del default table 2 2>&1
E/SELinux ( 5478): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5478): in addTimaSignatureService
D/TimaKeyStoreProvider( 5478): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5478): Added TimaKesytore provider
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  761): android_net_utils_resetConnections in env=0x7996d268 clazz=0x6a700001 iface=wlan0 mask=0x3
D/ConnectivityService(  761): resetConnections(wlan0, 3)
,V/NativeCrypto( 1317): Read error: ssl=0x7bc16de8: I/O error during system call, Connection timed out
,I/chromium( 5367): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NativeCrypto( 1317): SSL shutdown failed: ssl=0x7bc16de8: I/O error during system call, Broken pipe
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@9
,D/ConnectivityService(  761): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): updateIfacesLocked()
V/NetworkStats(  761): performPollLocked(flags=0x1)
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): performPollLocked() took 17ms
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,I/System.out( 5478): Inside WakeupProvider
,I/System.out( 5478): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5478): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5478): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5478): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5478): initQueue()
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  761): Killing 4460:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,I/ApplicationPolicy(  761): updateDataUsageMap
,D/Tethering(  761): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  761): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1446): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  761): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  761): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  761): ignore wifi update if we are not in OPENING or CLOSING
,I/PCWCLIENTTRACE_PushUtil( 5159): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5159): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5159): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3911): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): noConnectivity : true
,I/SELinux ( 5518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5518):  
,I/SELinux ( 5518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5518):  
I/SELinux ( 5518):  
,I/SELinux ( 5518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5518): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5518): >>>>> Normal User
,E/dalvikvm( 5518): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5518): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5518): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5518): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5518): Added TimaKesytore provider
,I/wpa_supplicant( 1961): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 1961): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1961): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1961): Trying to associate with  'G700'
I/wpa_supplicant( 1961): Re-associate with C0.AA.48
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1961): Cmd 35609 not handled
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5518, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  761): Killing 4476:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/wpa_supplicant( 1961): Cmd 35605 not handled
E/wpa_supplicant( 1961): Cmd 35847 not handled
E/wpa_supplicant( 1961): Cmd 35848 not handled
E/wpa_supplicant( 1961): Cmd 35605 not handled
I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1961): Associated with C0.AA.48
I/wpa_supplicant( 1961): freq(2412) increment count 2
I/wpa_supplicant( 1961): meet head of list.
I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
,E/Tethering(  761): No numeric data
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1961): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1961): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
,D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  761): performPollLocked(flags=0x1)
,D/WifiNative(  761): callSECApiVoid - ID [50]
,D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
,D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): performPollLocked() took 25ms
D/WifiP2pService(  761): InactiveState{ what=143375 }
D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,I/SELinux ( 5535): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5535):  
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 51% free 9512K/19056K, paused 2ms+3ms, total 27ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9512K/19056K, paused 2ms+2ms, total 19ms
I/SELinux ( 5535): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5535):  
I/SELinux ( 5535):  
,I/SELinux ( 5535): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5535): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5535): >>>>> Normal User
,E/dalvikvm( 5535): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5535): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9512K/19056K, paused 2ms+2ms, total 22ms
,D/TimaKeyStoreProvider( 5535): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5535): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5535): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5535, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  761): Killing 4498:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5551): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5551):  
,I/dhcpcd  ( 5547): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5547): bssid match
,I/SELinux ( 5551): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5551):  
I/SELinux ( 5551):  
,I/SELinux ( 5551): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5551): >>>>> Normal User
,E/dalvikvm( 5551): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5551): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5551): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5551): Added TimaKesytore provider
,D/SSRMv2:SIOP(  761): SIOP:: AP = 320, Delta = 10
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5551, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5551): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5551): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450438039546
,I/KLMS-2.3.201 : ( 5551): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  761): Killing 4515:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5567): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5567):  
,I/SELinux ( 5567): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5567):  
I/SELinux ( 5567):  
,I/SELinux ( 5567): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5567): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5567): >>>>> Normal User
,E/dalvikvm( 5567): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5567): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5567): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5567): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5567): Added TimaKesytore provider
,D/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5567, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4068): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4068): [BDLM] already registered in spp
I/SA      ( 4068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4068): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4068): [OR] == isSIMCardReady false ==
I/SA      ( 4068): [SCU] == networkStateCheck == false
,I/SA      ( 4068): [OR] onReceive END
I/ActivityManager(  761): Killing 4640:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SELinux ( 5582): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5582):  
,I/SELinux ( 5582): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5582):  
I/SELinux ( 5582):  
,I/SELinux ( 5582): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5582): >>>>> Normal User
,E/dalvikvm( 5582): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5582): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5582): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5582): Added TimaKesytore provider
,I/sCloudBackupApp( 5582): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5582): Other Intent
,D/com.samsung.app( 1446): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1446): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  761): Killing 4677:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5595): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5595):  
,I/SELinux ( 5595): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5595):  
I/SELinux ( 5595):  
,I/SELinux ( 5595): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5595): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5595): >>>>> Normal User
,E/dalvikvm( 5595): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5595): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5595): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5595): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5595): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5595, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  761): Killing 4661:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4119): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4119): getCountryCode(): countryCode = PL
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4119): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4119): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4119): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5608): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5608):  
,I/SELinux ( 5608): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5608):  
I/SELinux ( 5608):  
,I/SELinux ( 5608): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5608): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5608): >>>>> Normal User
,E/dalvikvm( 5608): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5608): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5608): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5608): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5608): Added TimaKesytore provider
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5608): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5608): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5608): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5608): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5608): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5608): Binding Chromium to the main looper Looper (main, tid 1) {426dbf48}
,I/chromium( 5608): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5608): Initializing chromium process, renderers=0
,W/chromium( 5608): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5608): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5608): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5608): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5608): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5608): Remote Branch: 
I/Adreno-EGL( 5608): Local Patches: 
I/Adreno-EGL( 5608): Reconstruct Branch: 
,I/NSApplication( 5608): Starting up...
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5608, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3355): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a0e510
I/ActivityManager(  761): Killing 3038:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5643): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5643):  
,I/SELinux ( 5643): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5643):  
I/SELinux ( 5643):  
,I/SELinux ( 5643): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5643): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5643): >>>>> Normal User
,E/dalvikvm( 5643): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5643): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5643): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5643): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5643): Added TimaKesytore provider
,E/SMD     (  242): DCD ON
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,I/SELinux ( 5668): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5668):  
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
I/ActivityManager(  761): Killing 4797:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5668): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5668):  
I/SELinux ( 5668):  
,I/SELinux ( 5668): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5668): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5668): >>>>> Normal User
,E/dalvikvm( 5668): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5668): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5688):  
,D/TimaKeyStoreProvider( 5668): in addTimaSignatureService
W/ActivityManager(  761): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5668): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5668): Added TimaKesytore provider
,I/ActivityManager(  761): Killing 4817:com.wssyncmldm/1000 (adj 15): empty #43
,I/SELinux ( 5688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5688):  
I/SELinux ( 5688):  
,I/SELinux ( 5688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5688): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5688): >>>>> Normal User
,E/dalvikvm( 5688): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5688): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5688): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5688): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5688): Added TimaKesytore provider
,D/BadgeProvider( 5668): onCreate
,D/BadgeProvider( 5668): DatabaseHelper
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5668, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5668): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5688, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5668): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5668): sendNotify, [notify] : null
D/BadgeProvider( 5668): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5668): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5668): update, [UpdateCount] : 1
,D/Launcher.Model( 1249): reloadBadges entered.
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  761): Killing 4665:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/WifiP2pService(  761): InactiveState{ what=143375 }
,D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,I/iu.UploadsManager( 1781): num queued entries: 0
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
I/iu.UploadsManager( 1781): num updated entries: 0
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,I/iu.SyncManager( 1781): NEXT; no task
,D/WifiStateMachine(  761): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  761): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  761): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
,D/WifiStateMachine(  761): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  761): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  761): mBoosterFLAG : 2
,I/WifiTrafficPoller(  761): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService(  761): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  761): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  761): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  761): handleConnectivityChange: setting default proxy info 
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  239): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/Toast   ( 1299):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1299): showing allowed
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,V/RouteController(  239): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  248): id=19 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/PowerManagerService(  761): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=761
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/RouteController(  239): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): updateIfacesLocked()
V/NetworkStats(  761): performPollLocked(flags=0x1)
V/NetworkStats(  761): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): performPollLocked() took 17ms
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/Tethering(  761): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  761): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/accuweather( 1446): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/LocSvc_java(  761): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  761): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  761): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3911): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5159): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5159): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5159): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 5551): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5551): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450438041946
,I/KLMS-2.3.201 : ( 5551): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2555): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2555): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2555): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2555): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2443): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5748): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5748):  
,I/SELinux ( 5752): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5752):  
,I/SELinux ( 5748): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5748):  
I/SELinux ( 5748):  
,I/SELinux ( 5748): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5748): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5748): >>>>> Normal User
,E/dalvikvm( 5748): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5748): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5748): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5748): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5748): Added TimaKesytore provider
I/SELinux ( 5752): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5752):  
I/SELinux ( 5752):  
,I/SELinux ( 5752): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5752): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5752): >>>>> Normal User
,E/dalvikvm( 5752): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5752): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5752): in addTimaSignatureService
,I/SA      ( 4068): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4068): [BDLM] already registered in spp
,I/SA      ( 4068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4068): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4068): [OR] == isSIMCardReady false ==
I/SA      ( 4068): [SCU] == networkStateCheck == true
,I/SA      ( 4068): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4068): isChinaCountryCode : false
D/TimaKeyStoreProvider( 5752): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 4068): [OR] == networkStateCheck true ==
,D/ActivityThread( 5752): Added TimaKesytore provider
,I/SA      ( 4068): [OR] GetMyCountryZoneTask
,I/SA      ( 4068): [OR] onReceive END
,I/SA      ( 4068): [SRS] prepareGetMyCountryZone
,I/SA      ( 4068): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4068): [SSP] query invoked
,I/SA      ( 4068): [TPMU] GetMccFromDB : null
,I/SA      ( 4068): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4068): [TPM] isNoProxy(default) : true
,I/SA      ( 4068): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5582): Other Intent
,D/com.samsung.app( 1446): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1446): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4119): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4119): getCountryCode(): countryCode = PL
,V/KVNProvider( 5752): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5752): getFindoCursor query string : 
D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4119): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4119): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4119): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 5752): getTagSearchCursor() tagSearchCursor count : 0
,D/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3355): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a0e510
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
I/ActivityManager(  761): Killing 4254:com.android.calendar/u0a142 (adj 15): empty #43
,D/WaitQueueForNetworkActivate( 4228): notifyNetworkActivated
,D/hcjo    ( 4228): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4228): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4228): exit::IDLE
,D/InitializeManagerStateMachine( 4228): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4228): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4228): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4228): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4228): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4228): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4228): entry::SUCCESS
,D/hcjo    ( 4228): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4228): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4228): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4228): exit::SUCCESS
,D/InitializeManagerStateMachine( 4228): entry::IDLE
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
,I/iu.SyncManager( 1781): NEXT; no task
,D/dalvikvm(  761): GC_EXPLICIT freed 2479K, 58% free 23918K/56092K, paused 12ms+18ms, total 146ms
,I/PhenotypeConfigurator( 1210): Scheduling Phenotype for one-off execution 6144 seconds from now (1450438042686)
,D/GetConfigurationSnapshotOperation( 1210): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1210): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1210): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1210): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1210): Using platform SSLCertificateSocketFactory
,I/SA      ( 4068): [RC New] [v2liruge] api execute + 690
,I/SA      ( 4068): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4068): AsyncTask #2 calls detatch()
,I/SA      ( 4068): [TPMU] getNetworkMcc : 
,D/LocationManagerService(  761): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SA      ( 4068): [SCU] saveMccToPreferece Start
,I/SA      ( 4068): [SCU] RegionMCC : 260
,I/SA      ( 4068): [SSP] query invoked
,I/SA      ( 4068): [TPMU] GetMccFromDB : null
I/SA      ( 4068): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4068): [SCU] saveMccToPreferece End
,I/SA      ( 4068): [RC New] executeRequest [v2liruge] end. 719
,I/SA      ( 4068): [RC New] Execute end
,I/SA      ( 4068): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4068): [OR] GetMyCountryZoneTask Success
,I/dalvikvm( 1210): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1210): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1210): Thread-109(HTTPLog):isShipBuild true
,I/System.out( 1210): Thread-109(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 5367): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5367): 
,D/ConnectivityService(  761): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 1210): GC_CONCURRENT freed 1597K, 38% free 11872K/19056K, paused 3ms+5ms, total 56ms
,I/HarmonyEASService(  761): Updating for all 1
,D/LocationManagerService(  761): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,W/WifiP2pStateTracker(  761): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  761): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  761):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  761): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  761): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  761): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager(  761): Killing 4448:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/SurfaceFlinger(  248): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  248): id=19 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  761): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=761 (0x0)
,D/PowerManagerService(  761): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=761, ws=WorkSource{1000}) (elapsedTime=3525)
,I/GAV2    ( 5608): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  242): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5159): [hasSamungAccount] - No Samsung Account
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  761): stay LED for fully charged
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  761): mCoverManager.getCoverState() : true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/linker  ( 5159): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5159): ================================================
,I/CSTORAGE( 5159):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 5159): ================================================
D/dalvikvm( 5159): No JNI_OnLoad found in /system/lib/libterrier.so 0x42a082e8, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5159): [GetString-S]
,I/terrier ( 5159): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5159): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5159): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5159): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5159): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5159): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5159): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5159): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5159): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5159): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5159): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5159): [ensureRegistration] - No Samsung account
,D/Finsky  ( 3695): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3695): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRMv2:SIOP(  761): SIOP:: AP = 310, Delta = -10
,E/SMD     (  242): DCD ON
,D/CaptivePortalTracker(  761): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  761): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  761): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  761): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  761): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  761): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  761): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/Watchdog(  761): !@Sync 4
,D/PreloadUpdateManagerStateMachine( 4228): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4228): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4228): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4228): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4228): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4228): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4228): entry::IDLE
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 293, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService(  761): [PWL] Off : 75s ago
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,E/SMD     (  242): DCD ON
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4119): Breath 16431 latestRequest time : 1450438042181 current time : 1450438058612
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = -10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 296, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 294, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  761): !@Sync 5
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService(  761): [PWL] Off : 105s ago
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 46408 latestRequest time : 1450438042181 current time : 1450438088589
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  761): !@Sync 6
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 76402 latestRequest time : 1450438042181 current time : 1450438118590
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  761): !@Sync 7
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 106411 latestRequest time : 1450438042181 current time : 1450438148592
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  761): !@Sync 8
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 136407 latestRequest time : 1450438042181 current time : 1450438178597
,D/Headlines( 4119): stop 
,D/Headlines( 4119): Breath.onDestroy : 
,I/ActivityManager(  761): Killing 4622:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  761): !@Sync 9
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService(  761): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  761): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  761): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  761): initializing...
,I/TLC_TIMA_PKM_initialize(  761): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  761): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  761): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  761): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  761): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  761): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  761): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  761): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  761): App is not loaded in QSEE
,D/QSEECOMAPI: (  761): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  761): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  761): Trustlet response is completed
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  761): !@Sync 10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 275s ago
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,I/SELinux ( 5881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5881):  
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/dalvikvm(  249): GC_EXPLICIT freed 42K, 51% free 9512K/19056K, paused 13ms+26ms, total 280ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9512K/19056K, paused 20ms+27ms, total 185ms
,I/SELinux ( 5881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5881):  
I/SELinux ( 5881):  
,I/SELinux ( 5881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5881): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5881): >>>>> Normal User
,E/dalvikvm( 5881): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5881): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9512K/19056K, paused 19ms+33ms, total 199ms
,D/TimaKeyStoreProvider( 5881): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5881): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5881): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5881, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  761): Killing 4575:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 11
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5367): Connected to the server!
I/jxcore-log( 5367): 
,I/chromium( 5367): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5367): --- start :testFindPeers.js---
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): testFindPeers created [object Object]
I/jxcore-log( 5367): 
,I/jxcore-log( 5367): serverPort is 8876
I/jxcore-log( 5367): 
,I/dalvikvm( 5367): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5367): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5367): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 5367): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 5367): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 5367): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 5367): Shutting down VM
,W/dalvikvm( 5367): threadid=1: thread exiting with uncaught exception (group=0x41c3dda0)
,E/AndroidRuntime( 5367): FATAL EXCEPTION: main
E/AndroidRuntime( 5367): Process: com.test.thalitest, PID: 5367
E/AndroidRuntime( 5367): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 5367): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 5367): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 5367): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 5367): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 5367): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 5367): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 5367): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 5367): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 5367): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 5367): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5367): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5367): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5367): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 5367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 5367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 5367): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 5367): Sending signal. PID: 5367 SIG: 9
,D/CrashAnrDetector(  761): processName: com.test.thalitest
,D/CrashAnrDetector(  761): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager(  761): Process com.test.thalitest (pid 5367) (adj 1) has died.
,I/WindowState(  761): WIN DEATH: Window{44b22ef0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  248): id=17 Removed NainActivit (7/12),
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5926): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5926):  
,I/SELinux ( 5926): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5926):  
I/SELinux ( 5926):  
,I/SELinux ( 5926): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5926): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5926): >>>>> Normal User
,E/dalvikvm( 5926): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
,E/SELinux ( 5926): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5926): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5926): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5926): Added TimaKesytore provider
,D/InputDispatcher(  761): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  248): id=20 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (233 us)
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5926, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5926, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,V/WebViewChromium( 5926): Binding Chromium to the background looper Looper (main, tid 1) {426d8378}
,I/chromium( 5926): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5926): Initializing chromium process, renderers=0
,W/chromium( 5926): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5926): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5926): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5926): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5926): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5926): Remote Branch: 
I/Adreno-EGL( 5926): Local Patches: 
I/Adreno-EGL( 5926): Reconstruct Branch: 
,I/dalvikvm( 5926): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 5926): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5926): VFY: replacing opcode 0x6e at 0x0016
,I/dalvikvm( 5926): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5926): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5926): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5926): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 5926): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5926): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
,W/dalvikvm( 5926): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5926): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5926): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,I/dalvikvm( 5926): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5926): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 5926): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5926): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5926): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5926): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5926): CordovaWebView is running on device made by: samsung
,I/SurfaceFlinger(  248): id=21 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5926): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5926): Enabling debug mode 0
,W/AwContents( 5926): nativeOnDraw failed; clearing to background color.
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/WindowManager(  761): Screen frozen for +491ms due to Window{44bcec78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  248): id=22 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  248): id=23 createSurf (720x2560),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  248): id=24 createSurf (1440x1280),-1 flag=20004, ClackSurfac
,I/SurfaceFlinger(  248): id=25 createSurf (720x2560),-1 flag=20004, ClackSurfac
,D/InputDispatcher(  761): setInputDispatchMode: enabled=0, frozen=0
,I/SurfaceFlinger(  248): id=20 Removed TcreenshotS (12/17)
,I/SurfaceFlinger(  248): id=20 Removed TcreenshotS (-2/17)
I/SurfaceFlinger(  248): id=22 Removed ClackSurfac (12/16)
I/SurfaceFlinger(  248): id=22 Removed ClackSurfac (-2/16)
,I/SurfaceFlinger(  248): id=23 Removed ClackSurfac (12/15)
I/SurfaceFlinger(  248): id=23 Removed ClackSurfac (-2/15)
,I/SurfaceFlinger(  248): id=24 Removed ClackSurfac (12/14)
,I/SurfaceFlinger(  248): id=24 Removed ClackSurfac (-2/14)
,I/SurfaceFlinger(  248): id=25 Removed ClackSurfac (12/13)
,I/SurfaceFlinger(  248): id=25 Removed ClackSurfac (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/WindowManager(  761): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/JsMessageQueue( 5926): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 5926): Trying to load lib /data/app-lib/com.test.thalitest-58/libjxcore.so 0x429ff0c8
,D/dalvikvm( 5926): Added shared lib /data/app-lib/com.test.thalitest-58/libjxcore.so 0x429ff0c8
D/jxcore_app_log( 5926): JniHelper::setJavaVM(0x41c2a4f8), pthread_self() = 2033132472
,D/JX-Cordova( 5926): jxcore cordova android initializing
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/dalvikvm( 5926): GC_CONCURRENT freed 4896K, 33% free 12796K/19056K, paused 4ms+4ms, total 65ms
,D/dalvikvm( 5926): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
D/dalvikvm( 5926): WAIT_FOR_CONCURRENT_GC blocked 33ms
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5926): GC_FOR_ALLOC freed 4696K, 28% free 15743K/21820K, paused 41ms, total 41ms
,D/dalvikvm(  761): GC_EXPLICIT freed 3107K, 58% free 23914K/56092K, paused 7ms+17ms, total 178ms
,D/dalvikvm( 5926): GC_FOR_ALLOC freed 5090K, 32% free 16757K/24508K, paused 44ms, total 44ms
,I/dalvikvm-heap( 5926): Grow heap (frag case) to 22.055MB for 2475476-byte allocation
,D/dalvikvm( 5926): GC_FOR_ALLOC freed 3780K, 36% free 17441K/26928K, paused 32ms, total 32ms
,D/dalvikvm( 5926): GC_FOR_ALLOC freed 1236K, 36% free 17344K/26928K, paused 28ms, total 28ms
,W/jxcore-log( 5926): Initializing JXcore engine
,W/jxcore-log( 5926): JXcore engine is ready
,W/jxcore-log( 5926): Starting JXcore engine
,W/jxcore-log( 5926): Platform android
W/jxcore-log( 5926): 
,W/jxcore-log( 5926): Process ARCH arm
W/jxcore-log( 5926): 
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5926): JXcore Cordova bridge is ready!
I/jxcore-log( 5926): 
,W/jxcore-log( 5926): JXcore engine is started
,I/chromium( 5926): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5926): Toggling radios to true
I/jxcore-log( 5926): 
,D/BluetoothAdapter( 5926): enable(): BT is already enabled..!
,I/WifiManager( 5926): packageName : com.test.thalitest
I/WifiManager( 5926): setWifiEnabled : true
,I/WifiService(  761): setWifiEnabled: true pid=5926, uid=10179
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5926, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  761): Failed getting userId using ActivityManagerNative
W/WifiService(  761): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5926, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  761): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  761): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  761): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  761): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  761): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  761): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService(  761): disconnect: pid=5926, uid=10179
I/wpa_supplicant( 1961): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 5926): Radios toggled
I/jxcore-log( 5926): 
I/jxcore-log( 5926): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5926): 
I/jxcore-log( 5926): Perf Test app loaded loaded
I/jxcore-log( 5926): 
,I/jxcore-log( 5926): check test folder
I/jxcore-log( 5926): 
,I/jxcore-log( 5926): found test : ./testFindPeers.js
I/jxcore-log( 5926): 
,I/wpa_supplicant( 1961): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1961): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1961): Cmd 35605 not handled
,E/wpa_supplicant( 1961): Cmd 35605 not handled
,I/wpa_supplicant( 1961): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
D/Tethering(  761): interfaceStatusChanged wlan0, false
,D/Tethering(  761): InitialState.processMessage what=4
,E/Tethering(  761): No numeric data
I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
V/NetworkStats(  761): performPollLocked(flags=0x1)
,I/jxcore-log( 5926): found test : ./testSendData.js
I/jxcore-log( 5926): 
I/wpa_supplicant( 1961): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1961): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1961): First Scan Start
,I/wpa_supplicant( 1961): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  761): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  761): ignore requestNetworkTransitionWakelock airplane:true
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/WifiP2pService(  761): InactiveState{ what=143375 }
D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/NetworkStats(  761): performPollLocked() took 36ms
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/CommandListener(  239): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
D/ConnectivityService(  761): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  761): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  761): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  761): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  761): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  761): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  761): Attempting to switch to mobile
D/ConnectivityService(  761): Attempting to switch to BLUETOOTH_TETHER
,V/RouteController(  239): /system/bin/ip -6 route del default table 2 2>&1
I/wpa_supplicant( 1961): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1961): Skip scan - already scanning
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService(  761): InactiveState{ what=143375 }
D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,V/RouteController(  239): RTNETLINK answers: No such process
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/RouteController(  239): /system/bin/ip -6 rule del table 2 2>&1
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  761): route cmd failed: 
W/NetworkManagementService(  761): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '61 route del src v6 2' failed with '400 61 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  761): '
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  761): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  761): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  761): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  761): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  239): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  761): android_net_utils_resetConnections in env=0x7996d268 clazz=0xa8300001 iface=wlan0 mask=0x3
,D/ConnectivityService(  761): resetConnections(wlan0, 3)
E/WifiStateMachine(  761): Error! unhandled message{ when=-109ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  761): Error! unhandled message{ when=-108ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  761): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,V/NativeCrypto( 1317): Read error: ssl=0x7bc16de8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1317): SSL shutdown failed: ssl=0x7bc16de8: I/O error during system call, Broken pipe
,I/chromium( 5926): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  761): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): updateIfacesLocked()
,V/NetworkStats(  761): performPollLocked(flags=0x1)
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): performPollLocked() took 18ms
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,E/SMD     (  242): DCD ON
,I/ApplicationPolicy(  761): updateDataUsageMap
,D/Tethering(  761): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  761): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1446): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5159): SPPPushClient is installed : true
,I/NetworkMonitor( 3911): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_PushUtil( 5159): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5159): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): noConnectivity : true
,D/LocSvc_java(  761): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  761): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  761): ignore wifi update if we are not in OPENING or CLOSING
,I/wpa_supplicant( 1961): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 1961): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1961): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1961): Trying to associate with  'G700'
I/wpa_supplicant( 1961): Re-associate with C0.AA.48
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1961): Cmd 35609 not handled
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,I/KLMS-2.3.201 : ( 5551): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5551): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450438290167
,I/KLMS-2.3.201 : ( 5551): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4068): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4068): [BDLM] already registered in spp
,I/SA      ( 4068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4068): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4068): [OR] == isSIMCardReady false ==
I/SA      ( 4068): [SCU] == networkStateCheck == false
,I/SA      ( 4068): [OR] onReceive END
,E/wpa_supplicant( 1961): Cmd 35605 not handled
E/wpa_supplicant( 1961): Cmd 35847 not handled
E/wpa_supplicant( 1961): Cmd 35848 not handled
E/wpa_supplicant( 1961): Cmd 35605 not handled
I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1961): Associated with C0.AA.48
D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
I/wpa_supplicant( 1961): freq(2412) increment count 3
I/wpa_supplicant( 1961): meet head of list.
I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
,E/Tethering(  761): No numeric data
I/SCloudBackupReceiver( 5582): Other Intent
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1961): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1961): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 1961): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/WifiNative(  761): callSECApiVoid - ID [50]
I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  761): performPollLocked(flags=0x1)
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
D/com.samsung.app( 1446): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
D/com.samsung.app( 1446): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): performPollLocked() took 34ms
D/WifiP2pService(  761): InactiveState{ what=143375 }
,D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
D/Headlines( 4119): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 4119): getCountryCode(): countryCode = PL
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/Headlines( 4119): Breath.onCreate
,D/Headlines( 4119): Breath timer started. interval : 30000
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4119): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4119): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4119): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager(  761): waitForAlarm result :8
,D/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3355): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a0e510
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
,I/iu.SyncManager( 1781): NEXT; no task
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1299): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1299): MountReceiver.mPrefHandler - 7002
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 88 latestRequest time : 1450438290294 current time : 1450438290382
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,I/dhcpcd  ( 6016): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6016): bssid match
,E/Watchdog(  761): !@Sync 12
,D/WifiP2pService(  761): InactiveState{ what=143375 }
,D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  761): VerifyingLinkState enter
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
E/SMD     (  242): DCD ON
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  761): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  761): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
D/ConnectivityService(  761): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine(  761): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  761): mBoosterFLAG : 2
,I/WifiTrafficPoller(  761): current booster mode : BTCoexMode
D/ConnectivityService(  761): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  761): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  761): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  761): handleConnectivityChange: setting default proxy info 
,V/RouteController(  239): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1299): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1299): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/Toast   ( 1299):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1299): showing allowed
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,V/RouteController(  239): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  248): id=26 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,V/RouteController(  239): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/PowerManagerService(  761): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=761
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/NearbySettings( 1299): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1299): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): updateIfacesLocked()
,V/NetworkStats(  761): performPollLocked(flags=0x1)
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): performPollLocked() took 25ms
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,I/jxcore-log( 5926): Connected to the server!
I/jxcore-log( 5926): 
,I/chromium( 5926): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  761): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  761): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1446): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3911): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5159): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5159): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5159): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  761): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  761): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  761): ignore wifi update if we are not in OPENING or CLOSING
,I/KLMS-2.3.201 : ( 5551): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5551): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450438293771
,I/KLMS-2.3.201 : ( 5551): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5567): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
I/LocationTagReadyService( 2555): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2555): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2555): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2555): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2443): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 5752): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5752): getFindoCursor query string : 
,V/KVNProvider( 5752): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4068): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4068): [BDLM] already registered in spp
I/SA      ( 4068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4068): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4068): [OR] == isSIMCardReady false ==
I/SA      ( 4068): [SCU] == networkStateCheck == true
I/SA      ( 4068): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4068): isChinaCountryCode : false
I/SA      ( 4068): [OR] == networkStateCheck true ==
,I/SA      ( 4068): [OR] GetMyCountryZoneTask
I/SA      ( 4068): [OR] onReceive END
I/SA      ( 4068): [SRS] prepareGetMyCountryZone
I/SA      ( 4068): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4068): [SSP] query invoked
I/SA      ( 4068): [TPMU] GetMccFromDB : null
,I/SA      ( 4068): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4068): [TPM] isNoProxy(default) : true
,I/SA      ( 4068): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5582): Other Intent
,D/com.samsung.app( 1446): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1446): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
D/Headlines( 4119): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4119): getCountryCode(): countryCode = PL
D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4119): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4119): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4119): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4119): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3355): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3355): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a0e510
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4228): notifyNetworkActivated
,D/hcjo    ( 4228): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4228): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4228): exit::IDLE
,D/InitializeManagerStateMachine( 4228): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4228): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4228): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4228): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4228): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4228): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4228): entry::SUCCESS
,D/hcjo    ( 4228): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 4228): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4228): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4228): exit::SUCCESS
,D/InitializeManagerStateMachine( 4228): entry::IDLE
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
,I/iu.SyncManager( 1781): NEXT; no task
,I/jxcore-log( 5926): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5926): 
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/SA      ( 4068): [RC New] [v2liruge] api execute + 710
,I/SA      ( 4068): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4068): AsyncTask #3 calls detatch()
,I/SA      ( 4068): [TPMU] getNetworkMcc : 
,I/SA      ( 4068): [SCU] saveMccToPreferece Start
I/SA      ( 4068): [SCU] RegionMCC : 260
,I/SA      ( 4068): [SSP] query invoked
,I/SA      ( 4068): [TPMU] GetMccFromDB : null
I/SA      ( 4068): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4068): [SCU] saveMccToPreferece End
,I/SA      ( 4068): [RC New] executeRequest [v2liruge] end. 720
I/SA      ( 4068): [RC New] Execute end
I/SA      ( 4068): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4068): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  761): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  242): DCD ON
,E/WifiStateMachine(  761): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/WifiP2pStateTracker(  761): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  761): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  761):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  761): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  761): updateSourceRoutes : no source routing conditions
,I/SurfaceFlinger(  248): id=26 Removed Uoast (12/13)
,I/SurfaceFlinger(  248): id=26 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  761): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=761 (0x0)
,D/PowerManagerService(  761): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=761, ws=WorkSource{1000}) (elapsedTime=3580)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5159): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5159): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5159): [GetString-S]
,I/terrier ( 5159): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5159): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5159): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5159): Loaded image: APP id = 6
,D/QSEECOMAPI: ( 5159): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5159): QSEECom_shutdown_app, app_id = 6
,E/terrier ( 5159): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5159): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5159): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5159): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5159): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5159): [ensureRegistration] - No Samsung account
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/CaptivePortalTracker(  761): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  761): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  761): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  761): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  761): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  761): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  761): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 4228): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4228): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4228): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4228): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4228): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4228): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4228): entry::IDLE
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/ActivityManager(  761): Waited long enough for: ServiceRecord{44a239e8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 26451 latestRequest time : 1450438293887 current time : 1450438320339
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 13
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 56445 latestRequest time : 1450438293887 current time : 1450438350334
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 14
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 390s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 86444 latestRequest time : 1450438293887 current time : 1450438380331
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 15
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 116445 latestRequest time : 1450438293887 current time : 1450438410332
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 16
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  761): [PWL] Off : 455s ago
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 4119): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4119): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4119): Breath 146454 latestRequest time : 1450438293887 current time : 1450438440341
,D/Headlines( 4119): stop 
,D/Headlines( 4119): Breath.onDestroy : 
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 17
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  761): GC_CONCURRENT freed 3375K, 58% free 24038K/56092K, paused 21ms+48ms, total 564ms
,E/Watchdog(  761): !@Sync 18
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 19
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 525s ago
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  761): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  761): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  761): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 20
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 21
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,I/SensorManagerA(  761): getReportingMode :: sensor.mType = 5
D/LightsService(  761): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  761): LightSensor setDelay = 200000000
,D/Sensors (  761): LightSensor setSensorDelay = 200000000
,D/Sensors (  761): Light sensor flush: not enabled 0
,D/Sensors (  761): LightSensor enable = 1
,D/Sensors (  761): LightSensor enableSensor = 1
,D/SensorManager(  761): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  761): [PWL] Off : 600s ago
,D/Sensors (  761): LightSensor enable = 0
,D/Sensors (  761): LightSensor enableSensor = 0
,D/SensorManager(  761): unregisterListener ::   
,D/lights  (  761): led_pattern : 5 +
D/LightsService(  761): [SvcLED]  onSensorChanged::light value = 18
,D/lights  (  761): led_pattern : 5 -
D/LightsService(  761): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 22
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  761): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  761): <AppSync3 Whitelist>
,V/AlarmManager(  761): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 23
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 24
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  761): [PWL] Off : 680s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,E/SMD     (  242): DCD ON
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  761): !@Sync 25
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 26
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 27
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 765s ago
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 28
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 29
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/TimaService(  761): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  761): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  761): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  761): !@Sync 30
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 855s ago
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 31
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 32
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 33
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 950s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 34
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm(  761): GC_CONCURRENT freed 3596K, 57% free 23990K/55328K, paused 26ms+48ms, total 543ms
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 35
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 36
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  761): [PWL] Off : 1050s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 37
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 38
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 39
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/TimaService(  761): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  761): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  761): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,E/SMD     (  242): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  761): !@Sync 40
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 41
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 42
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  761): waitForAlarm result :4
,D/LightsService(  761): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  761): getReportingMode :: sensor.mType = 5
D/Sensors (  761): LightSensor setDelay = 200000000
D/Sensors (  761): LightSensor setSensorDelay = 200000000
D/Sensors (  761): Light sensor flush: not enabled 0
D/Sensors (  761): LightSensor enable = 1
D/Sensors (  761): LightSensor enableSensor = 1
D/SensorManager(  761): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  761): [SvcLED]  onSensorChanged::light value = 26
D/Sensors (  761): LightSensor enable = 0
D/Sensors (  761): LightSensor enableSensor = 0
D/SensorManager(  761): unregisterListener ::   
D/lights  (  761): led_pattern : 5 +
,D/lights  (  761): led_pattern : 5 -
D/LightsService(  761): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService(  761): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  761): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  761): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
V/AlarmManager(  761): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 43
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 44
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 45
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 46
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 47
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 1380s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 48
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,E/SMD     (  242): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 49
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  761): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  761): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  761): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 50
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/dalvikvm(  761): GC_CONCURRENT freed 3511K, 57% free 24030K/55328K, paused 24ms+49ms, total 600ms
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 51
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 1500s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 52
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 53
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 54
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  761): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 55
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,E/SMD     (  242): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 1625s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 56
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 57
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 58
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 59
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/TimaService(  761): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  761): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  761): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  761): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  761): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 60
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  761): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  761): Prepared write state in 129ms
,I/ProcessStatsService(  761): Prepared write state in 123ms
,I/ProcessStatsService(  761): Prepared write state in 58ms
,E/SMD     (  242): DCD ON
,I/ProcessStatsService(  761): Pruning old procstats: /data/system/procstats/state-2015-12-17-14-11-04.bin
,E/Watchdog(  761): !@Sync 61
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 62
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  761): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  761): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  761): <AppSync3 Whitelist>
,V/AlarmManager(  761): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,I/ActivityManager(  761): Killing 4721:com.google.android.talk/u0a105 (adj 15): empty for 1841s
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  761): !@Sync 63
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  761): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1924): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  242): DCD ON
D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  761): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
E/SMD     (  242): DCD ON
D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  761): mCoverManager.getCoverState() : true
D/BatteryService(  761): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
V/HeadsetService( 1924): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 1924): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/AndroidRuntime( 6470): 
D/AndroidRuntime( 6470): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6470): CheckJNI is OFF
D/AndroidRuntime( 6470): setted country_code = Poland
D/AndroidRuntime( 6470): setted countryiso_code = PL
D/AndroidRuntime( 6470): setted sales_code = XEO
D/AndroidRuntime( 6470): readGMSProperty: start
D/AndroidRuntime( 6470): readGMSProperty: already setted!!
D/AndroidRuntime( 6470): readGMSProperty: end
D/AndroidRuntime( 6470): addProductProperty: start
D/dalvikvm( 6470): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6470): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6470): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6470): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6470): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6470): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6470): failed to load memtrack module: -2
D/dalvikvm( 6470): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6470): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  761): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  761): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  761): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  761): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  761): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  761): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  761): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  761): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  761): getApplicationUninstallationEnabled
D/ApplicationPolicy(  761): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  761): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  761): START PACKAGE DELETE: observer{1127550008}
D/PackageManager(  761): pkg{<packageName>}
D/PackageManager(  761): user{0}
D/PackageManager(  761): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  761): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  761): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  761): Killing 5926:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  761): Killing 5668:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1807s
I/ActivityManager(  761): Killing 5357:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1816s
I/ActivityManager(  761): Killing 5343:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1816s
I/ActivityManager(  761): Killing 5322:com.samsung.helphub/1000 (adj 15): empty for 1816s
I/ActivityManager(  761): Killing 5309:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1817s
I/ActivityManager(  761): Killing 5280:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1817s
I/ActivityManager(  761): Killing 5256:com.google.android.apps.docs/u0a90 (adj 15): empty for 1817s
I/ActivityManager(  761): Killing 5243:com.sec.android.service.cm/u0a78 (adj 15): empty for 1817s
I/ActivityManager(  761): Killing 4702:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1818s
I/ActivityManager(  761): Killing 4366:com.android.mms/u0a48 (adj 15): empty for 1818s
I/ActivityManager(  761): Killing 5211:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1818s
I/ActivityManager(  761): Killing 4271:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1818s
I/ActivityManager(  761): Killing 5173:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1818s
I/ActivityManager(  761): Killing 5145:com.android.musicfx/u0a24 (adj 15): empty for 1819s
I/ActivityManager(  761): Killing 5133:com.samsung.groupcast/u0a15 (adj 15): empty for 1819s
I/ActivityManager(  761): Killing 5116:com.google.android.partnersetup/u0a14 (adj 15): empty for 1819s
I/ActivityManager(  761): Killing 5100:com.sec.android.inputmethod/1000 (adj 15): empty for 1819s
I/ActivityManager(  761): Killing 5073:com.android.defcontainer/u0a6 (adj 15): empty for 1820s
I/SurfaceFlinger(  248): id=21 Removed NainActivit (7/12)
I/SurfaceFlinger(  248): id=21 Removed NainActivit (-2/12)
I/SurfaceFlinger(  248): id=21 Removed NainActivit (-2/12)
I/WindowState(  761): WIN DEATH: Window{44bcec78 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/dalvikvm(  761): GC_CONCURRENT freed 3601K, 57% free 24083K/55328K, paused 9ms+10ms, total 128ms
D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 87ms
D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 71ms
D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 90ms
D/CountryDetector(  761): No listener is left
W/PackageSettings(  761): Skipping PackageSetting{429aeed8 com.example.hello/10181} due to missing metadata
D/PackageManager(  761): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 1781): GC_EXPLICIT freed 958K, 36% free 12273K/19056K, paused 4ms+11ms, total 55ms
D/QuickConnect[1.1][2] ( 3355): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/SQLiteConnectionPool( 1781): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/RCPManagerService(  761): PackageReceiver onReceive()
D/PackageManager(  761): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/HarmonyEASService(  761): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
W/GeofencerStateMachine( 1210): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1404): GC_EXPLICIT freed 4309K, 48% free 10035K/19056K, paused 6ms+4ms, total 74ms
I/SELinux ( 6500): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6500):  
D/dalvikvm( 2185): GC_EXPLICIT freed 1617K, 41% free 11314K/19056K, paused 5ms+7ms, total 113ms
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "smsto"
I/SELinux ( 6500): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6500):  
I/SELinux ( 6500):  
I/SELinux ( 6500): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6500): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6500): >>>>> Normal User
E/dalvikvm( 6500): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6500): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "mms"
D/TimaKeyStoreProvider( 6500): in addTimaSignatureService
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6500): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6500): Added TimaKesytore provider
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "mmsto"
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "smsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  248): id=27 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=6500, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  761): removePackageParticipantsLocked: uid=10179 #1
D/elm:14132( 6500): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6500): ELMEngine.ELMEngine( context ).
D/elm:14132( 6500): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6500): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6500): ElmAgentService : onCreate()
D/elm:14132( 6500): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6500): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6500): MDMBridge.getInstance()
D/elm:14132( 6500): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6500): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService(  761): Package has changed for user 0
D/EnterpriseDeviceManagerService(  761): Admin package name: com.google.android.gms
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6514): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6514):  
D/elm:14132( 6500): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6500): ElmAgentService : onDestroy().
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6514): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6514):  
I/SELinux ( 6514):  
I/SELinux ( 6514): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6514): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6514): >>>>> Normal User
E/dalvikvm( 6514): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6514): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  761): GC_EXPLICIT freed 1675K, 57% free 24172K/55328K, paused 22ms+17ms, total 286ms
D/PackageManager(  761): delete sourFile : 
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6514): in addTimaSignatureService
D/TimaKeyStoreProvider( 6514): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6514): Added TimaKesytore provider
D/AndroidRuntime( 6470): Shutting down VM
D/dalvikvm( 6470): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
D/PackageManager(  761): delete native library directory: 
D/PackageManager(  761): return delete result to caller: 1127550008
D/PackageManager(  761): returnCode: 1
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "smsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "mmsto"
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=6514, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/dalvikvm( 6514): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42a01b90, skipping init
I/SecureStorage( 6514): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6514): [INFO]: SPID(0x00000000)This device supports Secure Storage
D/Launcher( 1249): onRestart, Launcher: 1118467816
D/Launcher( 1249): onStart, Launcher: 1118467816
D/Launcher.HomeView( 1249): onStart
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6514
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6514): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1446): [237392/5] SurfaceWidget drawing first frame
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6514): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6514
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  761): onPackageRemoved : com.test.thalitest
I/SurfaceFlinger(  248): id=28 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/UsbSettingsManager(  761): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/InputReader(  761): Processing first event
W/ApplicationsProvider( 1404): Could not fetch usage stats
W/ApplicationsProvider( 1404): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1404): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1404): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1404): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1404): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1404): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
