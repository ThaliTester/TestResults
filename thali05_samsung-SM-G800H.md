#### Test 50650278b28a87a_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5199): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5199):  
--------- beginning of /dev/log/system
I/ActivityManager(  766): Killing 3614:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 5199): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5199):  
I/SELinux ( 5199):  
I/SELinux ( 5199): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5199): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5199): >>>>> Normal User
E/dalvikvm( 5199): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5199): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5199): in addTimaSignatureService
D/TimaKeyStoreProvider( 5199): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5199): Added TimaKesytore provider
,I/SELinux ( 5225): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5225):  
I/ActivityManager(  766): Killing 4010:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  249): GC_EXPLICIT freed 45K, 49% free 9508K/18472K, paused 2ms+2ms, total 31ms
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9508K/18472K, paused 1ms+2ms, total 18ms
I/SELinux ( 5225): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5225):  
I/SELinux ( 5225):  
I/SELinux ( 5225): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5225): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5225): >>>>> Normal User
E/dalvikvm( 5225): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5225): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9508K/18472K, paused 2ms+13ms, total 30ms
D/TimaKeyStoreProvider( 5225): in addTimaSignatureService
D/TimaKeyStoreProvider( 5225): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5225): Added TimaKesytore provider
D/AndroidRuntime( 5223): 
D/AndroidRuntime( 5223): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5223): CheckJNI is OFF
D/AndroidRuntime( 5223): setted country_code = Poland
D/AndroidRuntime( 5223): setted countryiso_code = PL
D/AndroidRuntime( 5223): setted sales_code = XEO
D/AndroidRuntime( 5223): readGMSProperty: start
D/AndroidRuntime( 5223): readGMSProperty: already setted!!
D/AndroidRuntime( 5223): readGMSProperty: end
D/AndroidRuntime( 5223): addProductProperty: start
D/dalvikvm( 5223): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5223): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5223): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5223): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5223): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5225, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5225): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5225): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  766): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
I/SA      ( 4084): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4084): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4084): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4363): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2160): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/memtrack( 5223): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5223): failed to load memtrack module: -2
W/ContextImpl( 4725): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
D/dalvikvm( 5223): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 5258): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5258):  
D/AndroidRuntime( 5223): Calling main entry com.android.commands.am.Am
I/SELinux ( 5258): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5258):  
I/SELinux ( 5258):  
I/SELinux ( 5258): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5258): >>>>> Normal User
E/dalvikvm( 5258): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5258): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 2160): GC_CONCURRENT freed 6478K, 40% free 11211K/18472K, paused 6ms+4ms, total 80ms
D/dalvikvm( 2160): WAIT_FOR_CONCURRENT_GC blocked 43ms
D/TimaKeyStoreProvider( 5258): in addTimaSignatureService
D/TimaKeyStoreProvider( 5258): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5258): Added TimaKesytore provider
V/ApplicationPolicy(  766): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/IcingCorporaProvider( 2160): UpdateCorporaTask done [took 171 ms] updated apps [took 171 ms] 
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5258, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  766): mDVFSHelper.acquire()
I/SELinux ( 5273): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5273):  
D/LockPatternUtils( 1067): isPcwEnable = null
D/AndroidRuntime( 5223): Shutting down VM
D/dalvikvm( 5223): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
D/CapabilityManagerService New( 5258): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 5277): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5277):  
I/ActivityManager(  766): Killing 4022:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/ActivityManager(  766): Killing 4292:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5273): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5273):  
I/SELinux ( 5273):  
I/SELinux ( 5273): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5273): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5273): >>>>> Normal User
E/dalvikvm( 5273): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5273): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5273): in addTimaSignatureService
I/SELinux ( 5277): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5277):  
I/SELinux ( 5277):  
I/SELinux ( 5277): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/TimaKeyStoreProvider( 5273): Cannot add TimaSignature Service, License check Failed
E/SELinux ( 5277): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5277): >>>>> Normal User
E/dalvikvm( 5277): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
D/ActivityThread( 5273): Added TimaKesytore provider
E/SELinux ( 5277): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5277): in addTimaSignatureService
D/TimaKeyStoreProvider( 5277): Cannot add TimaSignature Service, License check Failed
I/SQLiteSecureOpenHelper( 2121): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2121): getDatabaseLocked(b,b,pwd)...
D/ActivityThread( 5277): Added TimaKesytore provider
D/LockPatternUtils( 1067): isPcwEnable = null
I/SurfaceFlinger(  248): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  248): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1259): destroyHardwareResources():1125115216
I/SurfaceFlinger(  248): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1451): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1259): onTrimMemory. Level: 20
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5273, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5273, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5273): Binding Chromium to the background looper Looper (main, tid 1) {421ce2c8}
I/chromium( 5273): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5273): Initializing chromium process, renderers=0
W/chromium( 5273): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5273): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5273): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5273): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5273): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5273): Remote Branch: 
I/Adreno-EGL( 5273): Local Patches: 
I/Adreno-EGL( 5273): Reconstruct Branch: 
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5277, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/dalvikvm( 5273): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5273): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5273): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5273): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5273): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5273): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5273): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5273): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5273): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5273): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5273): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5273): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5273): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5273): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5273): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5273): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5273): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5273): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5273): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  248): id=18 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5273): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5273): Enabling debug mode 0
W/AwContents( 5273): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  766): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
W/GAV2    ( 5277): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/JsMessageQueue( 5273): Set native->JS mode to OnlineEventsBridgeMode
I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5330): >>>>> Normal User
E/dalvikvm( 5330): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5330): Added TimaKesytore provider
D/AmoledAdjustTimer(  766): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
D/PackageIntentReceiver( 5330): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5330): Not GearManger package! 
I/SELinux ( 5349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5349):  
I/ActivityManager(  766): Killing 4035:com.sec.android.soagent/u0a37 (adj 15): empty #43
D/dalvikvm( 5273): Trying to load lib /data/app-lib/com.test.thalitest-21/libjxcore.so 0x424f5038
D/dalvikvm( 5273): Added shared lib /data/app-lib/com.test.thalitest-21/libjxcore.so 0x424f5038
D/jxcore_app_log( 5273): JniHelper::setJavaVM(0x416b5528), pthread_self() = 2025546952
D/JX-Cordova( 5273): jxcore cordova android initializing
I/dalvikvm( 5273): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5273): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5273): VFY: replacing opcode 0x6e at 0x0045
I/SELinux ( 5349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5349):  
I/SELinux ( 5349):  
I/SELinux ( 5349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5349): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5349): >>>>> Normal User
E/dalvikvm( 5349): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5349): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5349): in addTimaSignatureService
D/TimaKeyStoreProvider( 5349): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5349): Added TimaKesytore provider
D/MagazineService Version( 5349): Magazine-Channel: 13
D/MagazineService Version( 5349): Magazine-Provider: 13
D/MagazineService Version( 5349): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5349): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5349): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5349, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5349): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5362):  
D/MagazineService::MagazineService( 5349): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  766): Killing 4401:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,I/SELinux ( 5362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5362):  
I/SELinux ( 5362):  
,I/SELinux ( 5362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5362): >>>>> Normal User
,E/dalvikvm( 5362): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5362): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5362): Added TimaKesytore provider
,W/GAV2    ( 5277): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  766): Killing 4416:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,D/dalvikvm( 5273): GC_CONCURRENT freed 4911K, 31% free 12777K/18472K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 5273): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/SELinux ( 5376): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5376):  
I/ActivityManager(  766): Killing 4429:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5376): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5376):  
I/SELinux ( 5376):  
,I/SELinux ( 5376): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5376): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5376): >>>>> Normal User
E/dalvikvm( 5376): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5376): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5376): in addTimaSignatureService
D/TimaKeyStoreProvider( 5376): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5376): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5376, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5376): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5388): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5388):  
I/ActivityManager(  766): Killing 3598:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 5388): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5388):  
I/SELinux ( 5388):  
,I/SELinux ( 5388): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5388): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5388): >>>>> Normal User
,E/dalvikvm( 5388): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5388): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5388): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5388): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5388): Added TimaKesytore provider
,I/ActivityManager(  766): Killing 4458:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Finsky  ( 3707): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1648): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1648): Loading module APK com.google.android.play.games
I/dalvikvm( 1648): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1648): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1648): VFY: replacing opcode 0x6e at 0x0053
D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@9
,I/dalvikvm( 1648): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1648): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1648): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 1648): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1648): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1648): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1648): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1648): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 1648): GC_CONCURRENT freed 1896K, 37% free 11775K/18472K, paused 4ms+4ms, total 43ms
,D/dalvikvm( 5273): GC_FOR_ALLOC freed 4688K, 26% free 15773K/21264K, paused 33ms, total 33ms
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1648): Submit a task: k
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1648): Processing package: com.test.thalitest
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 1648): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1648): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,W/dalvikvm( 1648): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1648): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1648): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1648): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1648): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1648): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1648): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1648): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1648): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1648): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1648): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1648): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1648): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1648): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1648): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1648): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
D/dalvikvm( 1648): VFY: replacing opcode 0x6e at 0x0006
,E/SMD     (  242): DCD ON
,I/PeopleDatabaseHelper( 1648): cleanUpNonGplusAccounts done.
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5273): GC_FOR_ALLOC freed 5056K, 30% free 16785K/23952K, paused 35ms, total 35ms
,I/dalvikvm-heap( 5273): Grow heap (frag case) to 21.515MB for 2475476-byte allocation
,D/dalvikvm( 5273): GC_FOR_ALLOC freed 3776K, 34% free 17474K/26372K, paused 33ms, total 35ms
,D/dalvikvm( 5273): GC_FOR_ALLOC freed 1220K, 35% free 17372K/26372K, paused 28ms, total 28ms
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager(  766): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  766): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  766): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/jxcore-log( 5273): Initializing JXcore engine
,W/jxcore-log( 5273): JXcore engine is ready
,W/jxcore-log( 5273): Starting JXcore engine
,I/Icing   ( 1648): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1648): GC_CONCURRENT freed 1224K, 32% free 12566K/18472K, paused 4ms+4ms, total 33ms
,I/Icing   ( 1648): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 5273): Platform android
W/jxcore-log( 5273): 
,W/jxcore-log( 5273): Process ARCH arm
W/jxcore-log( 5273): 
,I/jxcore-log( 5273): JXcore Cordova bridge is ready!
I/jxcore-log( 5273): 
,W/jxcore-log( 5273): JXcore engine is started
,I/chromium( 5273): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4137): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/Headlines( 4137): Breath 68098 latestRequest time : 1449671213395 current time : 1449671281493
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1217): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1217): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,D/FactoryTest( 4790): Not factory mode
,D/FactoryTest( 4790): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4790): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4790): still no open session command from host, so toast
W/ContextImpl( 4790): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4790): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,D/dalvikvm(  766): GC_EXPLICIT freed 2619K, 60% free 23798K/58088K, paused 6ms+14ms, total 132ms
,V/ApplicationPolicy(  766): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  766): mDVFSHelper.acquire()
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/LockPatternUtils( 1067): isPcwEnable = null
,E/MTPRx   ( 4790): started activity for popup
,I/SQLiteSecureOpenHelper( 2121): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2121): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4790): PREF_DONT_ASK_AGAIN : false
,D/dalvikvm( 1305): GC_EXPLICIT freed 1471K, 42% free 10795K/18472K, paused 6ms+8ms, total 103ms
,D/SettingsReceiverActivity( 4790): dev.kiessupport is : TRUE
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/SurfaceFlinger(  248): id=19 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4790): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4790): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4790): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4790): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4790): Remote Branch: 
I/Adreno-EGL( 4790): Local Patches: 
I/Adreno-EGL( 4790): Reconstruct Branch: 
,I/HWUI    ( 4790): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4790): Enabling debug mode 0
,I/dalvikvm( 1217): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1217): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1217): VFY: replacing opcode 0x6e at 0x003d
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,E/SMD     (  242): DCD ON
I/System.out( 1217): Thread-108(HTTPLog):isShipBuild true
,I/System.out( 1217): Thread-108(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  766): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1217): GC_CONCURRENT freed 1639K, 37% free 11765K/18472K, paused 4ms+6ms, total 42ms
,I/GAV2    ( 5277): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5273): Toggling radios to true
I/jxcore-log( 5273): 
,W/PhenotypeConfigurator( 1217): Server returned 404
,D/BluetoothAdapter( 5273): enable(): BT is already enabled..!
,I/WifiManager( 5273): packageName : com.test.thalitest
,I/WifiManager( 5273): setWifiEnabled : true
,I/WifiService(  766): setWifiEnabled: true pid=5273, uid=10179
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5273, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  766): Failed getting userId using ActivityManagerNative
W/WifiService(  766): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5273, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  766): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  766): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  766): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  766): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  766): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  766): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  766): disconnect: pid=5273, uid=10179
,I/jxcore-log( 5273): Radios toggled
I/jxcore-log( 5273): 
,I/wpa_supplicant( 1962): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5273): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5273): 
,I/VacuumService( 1217): Vacuum at: now=1449671283101 tag=VacuumService
,I/jxcore-log( 5273): Perf Test app loaded loaded
I/jxcore-log( 5273): 
,I/jxcore-log( 5273): check test folder
I/jxcore-log( 5273): 
,I/jxcore-log( 5273): found test : ./testFindPeers.js
I/jxcore-log( 5273): 
,I/wpa_supplicant( 1962): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1962): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1962): Cmd 35605 not handled
,E/wpa_supplicant( 1962): Cmd 35605 not handled
,I/wpa_supplicant( 1962): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
,D/Tethering(  766): InitialState.processMessage what=4
,E/Tethering(  766): No numeric data
,D/Tethering(  766): sendTetherStateChangedBroadcast 0, 0, 0
,I/ConnectivityService(  766): defaultVal : 1, tetherEnabledInSettings : true
I/wpa_supplicant( 1962): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1962): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1962): First Scan Start
I/wpa_supplicant( 1962): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  766): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  766): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService(  766): InactiveState{ what=143375 }
,D/WifiP2pService(  766): P2pEnabledState{ what=143375 }
,D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): performPollLocked(flags=0x1)
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  766): evaluateTrafficStatsPolling
V/NetworkStats(  766): performPollLocked() took 36ms
D/NtpTrustedTime(  766): currentTimeMillis() cache hit
I/wpa_supplicant( 1962): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1962): Skip scan - already scanning
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  766): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  766): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  766): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  766): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  766): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  766): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/ConnectivityService(  766): Attempting to switch to mobile
D/ConnectivityService(  766): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService(  766): InactiveState{ what=143375 }
D/WifiP2pService(  766): P2pEnabledState{ what=143375 }
I/SELinux ( 5466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5466):  
D/STATUSBAR-IconMerger( 1067): checkOverflow(336), More:false, Req:false Child:2
D/NtpTrustedTime(  766): currentTimeMillis() cache hit
D/CommandListener(  239): Clearing all IP addresses on wlan0
D/NtpTrustedTime(  766): currentTimeMillis() cache hit
I/jxcore-log( 5273): found test : ./testSendData.js
I/jxcore-log( 5273): 
E/WifiStateMachine(  766): Error! unhandled message{ when=-27ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  766): Error! unhandled message{ when=-26ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  239): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  766): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@9
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine(  766): Error! unhandled message{ when=-8ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  239): RTNETLINK answers: No such file or directory
I/SELinux ( 5466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5466):  
I/SELinux ( 5466):  
,I/SELinux ( 5466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5466): >>>>> Normal User
,E/dalvikvm( 5466): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService(  766): route cmd failed: 
W/NetworkManagementService(  766): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 route del src v6 2' failed with '400 39 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  766): '
W/NetworkManagementService(  766): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  766): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  766): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  766): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  766): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  766): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  766): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  766): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  766): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  766): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  766): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  239): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such process
V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5466): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5466): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5466): Added TimaKesytore provider
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  766): android_net_utils_resetConnections in env=0x77cefe50 clazz=0x6a600001 iface=wlan0 mask=0x3
D/ConnectivityService(  766): resetConnections(wlan0, 3)
,V/NativeCrypto( 1305): Read error: ssl=0x7beb3cd8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1305): SSL shutdown failed: ssl=0x7beb3cd8: I/O error during system call, Broken pipe
,I/Choreographer( 5273): Skipped 129 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5273): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  766): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): updateIfacesLocked()
V/NetworkStats(  766): performPollLocked(flags=0x1)
V/NetworkStats(  766): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): performPollLocked() took 23ms
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,I/System.out( 5466): Inside WakeupProvider
,I/System.out( 5466): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5466): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5466): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5466): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5466): initQueue()
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  766): Killing 4474:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/ApplicationPolicy(  766): updateDataUsageMap
,D/Tethering(  766): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  766): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  766): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  766): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  766): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  766): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1451): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  766): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
I/PCWCLIENTTRACE_PushUtil( 5167): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5167): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5167): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5167): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 3943): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_SYSTEMReceiver( 5167): noConnectivity : true
,I/SELinux ( 5499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5499):  
,I/SELinux ( 5499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5499):  
I/SELinux ( 5499):  
,I/SELinux ( 5499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5499): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5499): >>>>> Normal User
,E/dalvikvm( 5499): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5499): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5499): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5499): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5499): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5499, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  766): Killing 4499:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5517): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5517):  
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 49% free 9508K/18472K, paused 2ms+2ms, total 23ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9508K/18472K, paused 2ms+2ms, total 18ms
,I/SELinux ( 5517): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5517):  
I/SELinux ( 5517):  
,I/SELinux ( 5517): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5517): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5517): >>>>> Normal User
,E/dalvikvm( 5517): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5517): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9508K/18472K, paused 3ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 5517): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5517): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5517): Added TimaKesytore provider
,I/wpa_supplicant( 1962): nl80211: Received scan results (9 BSSes)
,I/wpa_supplicant( 1962): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1962): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1962): Trying to associate with  'G700'
I/wpa_supplicant( 1962): Re-associate with C0.AA.48
,I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1962): Cmd 35609 not handled
D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5517, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,E/wpa_supplicant( 1962): Cmd 35605 not handled
E/wpa_supplicant( 1962): Cmd 35847 not handled
E/wpa_supplicant( 1962): Cmd 35848 not handled
E/wpa_supplicant( 1962): Cmd 35605 not handled
I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1962): Associated with C0.AA.48
I/wpa_supplicant( 1962): freq(2412) increment count 2
,I/wpa_supplicant( 1962): meet head of list.
,I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
D/Tethering(  766): interfaceLinkStateChanged wlan0, false
,D/Tethering(  766): interfaceStatusChanged wlan0, false
,D/Tethering(  766): interfaceLinkStateChanged wlan0, true
,D/Tethering(  766): interfaceStatusChanged wlan0, true
D/Tethering(  766): interfaceLinkStateChanged wlan0, true
,D/Tethering(  766): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering(  766): No numeric data
I/wpa_supplicant( 1962): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1962): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1962): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  766): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  766): interfaceLinkStateChanged wlan0, true
,D/Tethering(  766): interfaceStatusChanged wlan0, true
,D/WifiNative(  766): callSECApiVoid - ID [50]
I/ConnectivityService(  766): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  766): interfaceLinkStateChanged wlan0, true
D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/Tethering(  766): interfaceStatusChanged wlan0, true
D/Tethering(  766): interfaceLinkStateChanged wlan0, true
,D/Tethering(  766): interfaceStatusChanged wlan0, true
V/NetworkStats(  766): performPollLocked(flags=0x1)
,I/ActivityManager(  766): Killing 4520:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
V/NetworkStats(  766): performPollLocked() took 31ms
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
D/WifiP2pService(  766): InactiveState{ what=143375 }
D/WifiP2pService(  766): P2pEnabledState{ what=143375 }
,I/SELinux ( 5533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5533):  
,D/SSRMv2:SIOP(  766): SIOP:: AP = 330, Delta = 20
,I/SELinux ( 5533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5533):  
I/SELinux ( 5533):  
,I/SELinux ( 5533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5533): >>>>> Normal User
,E/dalvikvm( 5533): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5533): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5533): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5533, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5533): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5533): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449671284623
,I/KLMS-2.3.201 : ( 5533): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  766): Killing 1338:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 5545): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5545):  
,I/SELinux ( 5545): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5545):  
I/SELinux ( 5545):  
,I/SELinux ( 5545): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5545): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5545): >>>>> Normal User
,E/dalvikvm( 5545): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5545): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5545): in addTimaSignatureService
D/TimaKeyStoreProvider( 5545): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5545): Added TimaKesytore provider
,I/dhcpcd  ( 5549): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5549): bssid match
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5545, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
D/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 4084): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4084): [BDLM] already registered in spp
,I/SA      ( 4084): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 4084): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4084): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4084): [OR] == isSIMCardReady false ==
I/SA      ( 4084): [SCU] == networkStateCheck == false
,I/SA      ( 4084): [OR] onReceive END
I/ActivityManager(  766): Killing 4659:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SELinux ( 5569): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5569):  
,I/SELinux ( 5569): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5569):  
I/SELinux ( 5569):  
,I/SELinux ( 5569): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5569): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5569): >>>>> Normal User
,E/dalvikvm( 5569): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5569): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5569): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5569): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5569): Added TimaKesytore provider
,I/sCloudBackupApp( 5569): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5569): Other Intent
,I/ActivityManager(  766): Killing 4679:com.sec.android.app.voicenote/1000 (adj 15): empty #43
D/com.samsung.app( 1451): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1451): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5582): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5582):  
,I/SELinux ( 5582): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5582):  
I/SELinux ( 5582):  
,I/SELinux ( 5582): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5582): >>>>> Normal User
,E/dalvikvm( 5582): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5582): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5582): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5582): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5582, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  766): Killing 4739:com.google.android.talk/u0a105 (adj 15): empty #43
,D/Headlines( 4137): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4137): getCountryCode(): countryCode = PL
,D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 4137): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4137): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 4137): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4137): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4137): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4137): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5598): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5598):  
,I/SELinux ( 5598): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5598):  
I/SELinux ( 5598):  
,I/SELinux ( 5598): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5598): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5598): >>>>> Normal User
,E/dalvikvm( 5598): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5598): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5598): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5598): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5598): Added TimaKesytore provider
,E/SMD     (  242): DCD ON
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5598): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5598): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 5598): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5598): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5598): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5598): Binding Chromium to the main looper Looper (main, tid 1) {421d0f30}
,I/chromium( 5598): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5598): Initializing chromium process, renderers=0
,W/chromium( 5598): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5598): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5598): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5598): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5598): Remote Branch: 
I/Adreno-EGL( 5598): Local Patches: 
I/Adreno-EGL( 5598): Reconstruct Branch: 
,I/NSApplication( 5598): Starting up...
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5598, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3373): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3373): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3373): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42503280
I/ActivityManager(  766): Killing 3060:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5632): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5632):  
,I/SELinux ( 5632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5632):  
I/SELinux ( 5632):  
,I/SELinux ( 5632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5632): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5632): >>>>> Normal User
,E/dalvikvm( 5632): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5632): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5632): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5632): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5632): Added TimaKesytore provider
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
I/ActivityManager(  766): Killing 4824:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5651): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5651):  
,I/SELinux ( 5656): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5656):  
W/ActivityManager(  766): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5651): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5651):  
I/SELinux ( 5651):  
,I/SELinux ( 5651): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5651): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5651): >>>>> Normal User
,E/dalvikvm( 5651): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5651): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5651): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5651): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5651): Added TimaKesytore provider
,I/SELinux ( 5656): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5656):  
I/SELinux ( 5656):  
,I/SELinux ( 5656): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5656): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5656): >>>>> Normal User
,E/dalvikvm( 5656): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5656): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5656): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5656): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5656): Added TimaKesytore provider
,I/ActivityManager(  766): Killing 4845:com.wssyncmldm/1000 (adj 15): empty #43
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5651, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
D/BadgeProvider( 5656): onCreate
,D/BadgeProvider( 5656): DatabaseHelper
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5656, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5656): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/ActivityManager(  766): Killing 4698:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/BadgeProvider( 5656): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5656): sendNotify, [notify] : null
D/Launcher.Model( 1259): reloadBadges entered.
D/BadgeProvider( 5656): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5656): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5656): update, [UpdateCount] : 1
,I/iu.Environment( 1648): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1648): num queued entries: 0
,I/iu.UploadsManager( 1648): num updated entries: 0
,I/iu.SyncManager( 1648): NEXT; no task
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  766): InactiveState{ what=143375 }
,D/WifiP2pService(  766): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/WifiStateMachine(  766): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  766): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  766): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  766): evaluateTrafficStatsPolling
,D/WifiStateMachine(  766): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  766): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  766): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  766): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  766): mBoosterFLAG : 2
,I/WifiTrafficPoller(  766): current booster mode : BTCoexMode
D/ConnectivityService(  766): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  766): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  766): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1067): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  766): handleConnectivityChange: setting default proxy info 
,V/RouteController(  239): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/Toast   ( 1311):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1311): showing allowed
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,V/RouteController(  239): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/SurfaceFlinger(  248): id=20 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  766): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=766
V/RouteController(  239): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): updateIfacesLocked()
V/NetworkStats(  766): performPollLocked(flags=0x1)
V/NetworkStats(  766): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): performPollLocked() took 18ms
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/Tethering(  766): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  766): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  766): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/LocSvc_java(  766): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/LocSvc_java(  766): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  766): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1451): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5167): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5167): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5167): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5167): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3943): type=WIFI subType= reason=null isConnected=true
,I/KLMS-2.3.201 : ( 5533): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5533): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449671287242
,I/KLMS-2.3.201 : ( 5533): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2575): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/GalaxyFinderApplication( 2575): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2575): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2575): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5545): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2394): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5743): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5743):  
,I/SELinux ( 5743): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5743):  
I/SELinux ( 5743):  
I/SELinux ( 5743): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/SELinux ( 5747): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5747):  
,E/SELinux ( 5743): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5743): >>>>> Normal User
,E/dalvikvm( 5743): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5743): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5743): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5743): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5743): Added TimaKesytore provider
,I/SELinux ( 5747): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5747):  
I/SELinux ( 5747):  
I/SELinux ( 5747): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5747): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5747): >>>>> Normal User
,E/dalvikvm( 5747): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5747): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5747): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5747): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5747): Added TimaKesytore provider
,I/SA      ( 4084): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4084): [BDLM] already registered in spp
I/SA      ( 4084): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4084): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4084): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4084): [OR] == isSIMCardReady false ==
,I/SA      ( 4084): [SCU] == networkStateCheck == true
I/SA      ( 4084): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4084): isChinaCountryCode : false
I/SA      ( 4084): [OR] == networkStateCheck true ==
,I/SA      ( 4084): [OR] GetMyCountryZoneTask
,I/SA      ( 4084): [OR] onReceive END
,I/SA      ( 4084): [SRS] prepareGetMyCountryZone
,I/SA      ( 4084): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4084): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
,I/SA      ( 4084): [TPMU] GetMccFromDB : null
,V/KVNProvider( 5747): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5747): getFindoCursor query string : 
,I/SCloudBackupReceiver( 5569): Other Intent
I/SA      ( 4084): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4084): [TPM] isNoProxy(default) : true
,I/SA      ( 4084): [RC New] Execute method=[GET] start
,D/dalvikvm(  766): GC_EXPLICIT freed 2717K, 60% free 23721K/58088K, paused 7ms+14ms, total 162ms
,D/com.samsung.app( 1451): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1451): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4137): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4137): getCountryCode(): countryCode = PL
,V/KVNProvider( 5747): getTagSearchCursor() tagSearchCursor count : 0
D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4137): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4137): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4137): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4137): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4137): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4137): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3373): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3373): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3373): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42503280
I/ActivityManager(  766): Killing 4256:com.android.calendar/u0a142 (adj 15): empty #43
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
,D/RCPManagerService(  766): exchangeData() failure , invalid userId
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
,D/InitializeManagerStateMachine( 4228): exit::SUCCESS
,D/InitializeManagerStateMachine( 4228): entry::IDLE
,I/iu.Environment( 1648): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1648): num queued entries: 0
,I/iu.UploadsManager( 1648): num updated entries: 0
,I/iu.SyncManager( 1648): NEXT; no task
,I/PhenotypeConfigurator( 1217): Scheduling Phenotype for one-off execution 13335 seconds from now (1449671287988)
,D/GetConfigurationSnapshotOperation( 1217): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1217): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/AmoledAdjustTimer(  766): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,I/GoogleURLConnFactory( 1217): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  766): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/jxcore-log( 5273): BLE advertisement not supported: Build version is 19
I/jxcore-log( 5273): 
,I/SA      ( 4084): [RC New] [v2liruge] api execute + 644
,I/SA      ( 4084): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4084): AsyncTask #2 calls detatch()
,I/SA      ( 4084): [TPMU] getNetworkMcc : 
,I/SA      ( 4084): [SCU] saveMccToPreferece Start
,I/SA      ( 4084): [SCU] RegionMCC : 260
,I/SA      ( 4084): [SSP] query invoked
,I/SA      ( 4084): [TPMU] GetMccFromDB : null
I/SA      ( 4084): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4084): [SCU] saveMccToPreferece End
I/SA      ( 4084): [RC New] executeRequest [v2liruge] end. 660
,I/SA      ( 4084): [RC New] Execute end
I/SA      ( 4084): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4084): [OR] GetMyCountryZoneTask Success
,E/SMD     (  242): DCD ON
,D/LocationManagerService(  766): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  766): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  766): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager(  766): Killing 4694:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/SurfaceFlinger(  248): id=20 Removed Uoast (12/13)
,I/SurfaceFlinger(  248): id=20 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1),
,D/PowerManagerService(  766): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=766 (0x0)
,D/PowerManagerService(  766): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=766, ws=WorkSource{1000}) (elapsedTime=3475)
,I/HarmonyEASService(  766): Updating for all 1
,I/GAV2    ( 5598): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker(  766): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  766): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  766):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  766): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  766): updateSourceRoutes : no source routing conditions
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5167): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5167): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5167): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5167): ================================================
,I/CSTORAGE( 5167):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5167): ================================================
,D/dalvikvm( 5167): No JNI_OnLoad found in /system/lib/libterrier.so 0x424fd340, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5167): [GetString-S]
,I/terrier ( 5167): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5167): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5167): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5167): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5167): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5167): QSEECom_shutdown_app, app_id = 3
,E/terrier ( 5167): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5167): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5167): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5167): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5167): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5167): [ensureRegistration] - No Samsung account
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 310, Delta = -20
,D/Finsky  ( 3707): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3707): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  766): !@Sync 4
,D/CaptivePortalTracker(  766): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  766): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  766): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  766): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  766): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  766): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  766): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  766): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/SMD     (  242): DCD ON
,D/PreloadUpdateManagerStateMachine( 4228): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4228): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4228): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4228): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4228): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4228): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4228): entry::IDLE
,D/AmoledAdjustTimer(  766): prevTemp = 295, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 75s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,D/Headlines( 4137): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4137): Breath 15766 latestRequest time : 1449671287674 current time : 1449671303440
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = -10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 5
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 295, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 105s ago
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,D/Headlines( 4137): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4137): Breath 45772 latestRequest time : 1449671287674 current time : 1449671333447
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 6
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,D/Headlines( 4137): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4137): Breath 75755 latestRequest time : 1449671287674 current time : 1449671363429
,I/PowerManagerService(  766): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 7
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,D/Headlines( 4137): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4137): Breath 105754 latestRequest time : 1449671287674 current time : 1449671393428
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 180s ago
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 8
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,D/Headlines( 4137): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4137): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4137): Breath 135759 latestRequest time : 1449671287674 current time : 1449671423433
,D/Headlines( 4137): stop 
,D/Headlines( 4137): Breath.onDestroy : 
,I/ActivityManager(  766): Killing 4445:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5273): Connected to the server!
I/jxcore-log( 5273): 
,I/chromium( 5273): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 9
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 225s ago
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_initialize(  766): initializing...
,I/TLC_TIMA_PKM_initialize(  766): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  766): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  766): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  766): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  766): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  766): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  766): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  766): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  766): App is not loaded in QSEE
,D/QSEECOMAPI: (  766): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  766): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  766): Trustlet response is completed
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  766): !@Sync 10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :4
,I/SELinux ( 5867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5867):  
,I/PowerManagerService(  766): [PWL] Off : 275s ago
,I/PowerManagerService(  766): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  766): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  766): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=766, ws=WorkSource{10075}) (elapsedTime=154)
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 49% free 9508K/18472K, paused 8ms+20ms, total 206ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9508K/18472K, paused 18ms+20ms, total 146ms
,I/SELinux ( 5867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5867):  
I/SELinux ( 5867):  
,I/SELinux ( 5867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5867): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5867): >>>>> Normal User
,E/dalvikvm( 5867): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5867): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9508K/18472K, paused 9ms+22ms, total 144ms
,D/TimaKeyStoreProvider( 5867): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5867): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5867, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  766): Killing 4644:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 11
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 12
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 330s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 13
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm(  766): GC_CONCURRENT freed 3503K, 60% free 23681K/58088K, paused 23ms+50ms, total 559ms
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 14
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 390s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 15
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 16
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 455s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 17
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 18
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 19
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 525s ago
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  242): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 20
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 21
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  766): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,I/SensorManagerA(  766): getReportingMode :: sensor.mType = 5
,D/Sensors (  766): LightSensor setDelay = 200000000
,D/Sensors (  766): LightSensor setSensorDelay = 200000000
D/LightsService(  766): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  766): Light sensor flush: not enabled 0
,D/Sensors (  766): LightSensor enable = 1
,D/Sensors (  766): LightSensor enableSensor = 1
,D/SensorManager(  766): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  766): [PWL] Off : 600s ago
,D/Sensors (  766): LightSensor enable = 0
,D/Sensors (  766): LightSensor enableSensor = 0
,D/SensorManager(  766): unregisterListener ::   
D/LightsService(  766): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  766): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 22
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  766): !@Sync 23
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  766): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  766): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  766): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 24
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 680s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 25
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 26
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 27
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 765s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 28
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/dalvikvm(  766): GC_CONCURRENT freed 3444K, 60% free 23691K/58056K, paused 20ms+51ms, total 537ms
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 29
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  766): !@Sync 30
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 855s ago
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 31
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 32
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 33
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 950s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/ConnectivityService(  766): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 34
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 35
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 36
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1050s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 37
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 38
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 39
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  766): !@Sync 40
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 1155s ago
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 41
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,E/SMD     (  242): DCD ON
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :4
,I/SensorManagerA(  766): getReportingMode :: sensor.mType = 5
,D/Sensors (  766): LightSensor setDelay = 200000000
,D/LightsService(  766): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  766): LightSensor setSensorDelay = 200000000
D/Sensors (  766): Light sensor flush: not enabled 0
D/Sensors (  766): LightSensor enable = 1
D/Sensors (  766): LightSensor enableSensor = 1
D/SensorManager(  766): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  766): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  766): LightSensor enable = 0
D/Sensors (  766): LightSensor enableSensor = 0
,D/SensorManager(  766): unregisterListener ::   
D/LightsService(  766): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1648): Aggregate from 1449670478542 (log), 1449670478542 (data)
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 42
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 43
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  766): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  766): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  766): (AppSync) ### 0 added ###
,E/SMD     (  242): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1265s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 44
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/dalvikvm(  766): GC_CONCURRENT freed 3432K, 60% free 23716K/58056K, paused 21ms+51ms, total 542ms
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 45
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 46
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 47
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1380s ago,
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 48
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 49
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 50
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 51
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1500s ago
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 52
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 53
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 54
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 55
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  766): [PWL] Off : 1625s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 56
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 57
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 58
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 59
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,D/dalvikvm(  766): GC_CONCURRENT freed 3457K, 60% free 23741K/58056K, paused 19ms+38ms, total 848ms
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 60
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,E/SMD     (  242): DCD ON
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 61
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  766): Prepared write state in 134ms
,I/ProcessStatsService(  766): Prepared write state in 121ms
,E/SMD     (  242): DCD ON
,I/ProcessStatsService(  766): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-44-14.bin
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 62
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 63
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  766): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  766): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  766): (AppSync) ### 0 added ###
,I/ActivityManager(  766): Killing 5388:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5376:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5362:com.samsung.helphub/1000 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5349:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5330:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1801s
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  766): Killing 5277:com.google.android.apps.docs/u0a90 (adj 15): empty for 1802s
,I/ActivityManager(  766): Killing 5258:com.sec.android.service.cm/u0a78 (adj 15): empty for 1802s
,I/ActivityManager(  766): Killing 4725:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1802s
,I/ActivityManager(  766): Killing 4363:com.android.mms/u0a48 (adj 15): empty for 1802s
,I/ActivityManager(  766): Killing 5225:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1803s
,I/ActivityManager(  766): Killing 4274:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1803s
,I/ActivityManager(  766): Killing 5179:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1803s
,I/ActivityManager(  766): Killing 5153:com.android.musicfx/u0a24 (adj 15): empty for 1804s
,I/ActivityManager(  766): Killing 5138:com.samsung.groupcast/u0a15 (adj 15): empty for 1804s
,I/ActivityManager(  766): Killing 5123:com.google.android.partnersetup/u0a14 (adj 15): empty for 1804s
,I/ActivityManager(  766): Killing 5110:com.sec.android.inputmethod/1000 (adj 15): empty for 1804s
,I/ActivityManager(  766): Killing 5074:com.android.defcontainer/u0a6 (adj 15): empty for 1805s
,I/ActivityManager(  766): Killing 4601:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1857s
,E/SMD     (  242): DCD ON,
,D/CountryDetector(  766): No listener is left
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  766): waitForAlarm result :4
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): performPollLocked(flags=0x3)
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
V/NetworkStats(  766): performPollLocked() took 205ms
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,D/NtpTrustedTime(  766): currentTimeMillis() cache hit
,I/ActivityManager(  766): Killing 5466:com.vlingo.midas/u0a33 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5533:com.samsung.klmsagent/u0a18 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5517:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 3991:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5499:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 3943:com.google.android.music:main/u0a122 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5167:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 1311:com.android.settings/1000 (adj 15): empty for 1801s
,I/ActivityManager(  766): Killing 5656:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1802s
,I/SensorManagerA(  766): getReportingMode :: sensor.mType = 5
,D/Sensors (  766): LightSensor setDelay = 200000000
,D/LightsService(  766): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  766): LightSensor setSensorDelay = 200000000
D/Sensors (  766): Light sensor flush: not enabled 0
D/Sensors (  766): LightSensor enable = 1
D/Sensors (  766): LightSensor enableSensor = 1
D/SensorManager(  766): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  766): LightSensor enable = 0
,D/Sensors (  766): LightSensor enableSensor = 0
,D/SensorManager(  766): unregisterListener ::   
D/LightsService(  766): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  766): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService(  766): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  766): !@Sync 64
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1929): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1929): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  242): DCD ON
E/SMD     (  242): DCD ON
D/AndroidRuntime( 6286): 
D/AndroidRuntime( 6286): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6286): CheckJNI is OFF
D/AndroidRuntime( 6286): setted country_code = Poland
D/AndroidRuntime( 6286): setted countryiso_code = PL
D/AndroidRuntime( 6286): setted sales_code = XEO
D/AndroidRuntime( 6286): readGMSProperty: start
D/AndroidRuntime( 6286): readGMSProperty: already setted!!
D/AndroidRuntime( 6286): readGMSProperty: end
D/AndroidRuntime( 6286): addProductProperty: start
D/dalvikvm( 6286): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6286): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6286): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6286): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6286): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6286): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6286): failed to load memtrack module: -2
D/dalvikvm( 6286): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6286): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  766): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  766): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  766): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  766): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  766): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  766): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  766): START PACKAGE DELETE: observer{1123816784}
D/PackageManager(  766): pkg{<packageName>}
D/PackageManager(  766): user{0}
D/PackageManager(  766): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  766): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  766): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  766): getApplicationUninstallationEnabled
D/ApplicationPolicy(  766): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  766): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  766): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  766): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  766): Killing 5273:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/WindowState(  766): WIN DEATH: Window{42dbe388 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  248): id=18 Removed NainActivit (7/12)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/PackageSettings(  766): Skipping PackageSetting{42b67f78 com.example.hello/10180} due to missing metadata
D/PackageManager(  766): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1410): GC_EXPLICIT freed 4307K, 46% free 10029K/18472K, paused 2ms+4ms, total 43ms
D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
D/PackageManager(  766): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2160): GC_EXPLICIT freed 535K, 41% free 10953K/18472K, paused 101ms+3ms, total 129ms
D/AdaptiveEventManager( 1067): action=android.intent.action.PACKAGE_REMOVED
W/GeofencerStateMachine( 1217): Ignoring removeGeofence because network location is disabled.
I/InputReader(  766): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm(  766): GC_EXPLICIT freed 2380K, 60% free 23736K/58056K, paused 7ms+14ms, total 147ms
D/QuickConnect[1.1][2] ( 3373): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/dalvikvm( 1648): GC_EXPLICIT freed 945K, 34% free 12350K/18472K, paused 89ms+8ms, total 158ms
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "sms"
I/SELinux ( 6309): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6309):  
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "smsto"
D/RCPManagerService(  766): PackageReceiver onReceive()
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  766): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 6309): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6309):  
I/SELinux ( 6309):  
I/SELinux ( 6309): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6309): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6309): >>>>> Normal User
E/dalvikvm( 6309): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6309): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6309): in addTimaSignatureService
D/TimaKeyStoreProvider( 6309): Cannot add TimaSignature Service, License check Failed
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mmsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread( 6309): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "smsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  248): id=21 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mmsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6309): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=6309, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6309): ELMEngine.ELMEngine( context ).
D/elm:14132( 6309): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6309): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6309): ElmAgentService : onCreate()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6309): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6309): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6309): MDMBridge.getInstance()
D/elm:14132( 6309): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6309): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6324): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6324):  
D/EnterpriseDeviceManagerService(  766): Package has changed for user 0
D/EnterpriseDeviceManagerService(  766): Admin package name: com.google.android.gms
D/BackupManagerService(  766): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  766): removePackageParticipantsLocked: uid=10179 #1
D/elm:14132( 6309): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6309): ElmAgentService : onDestroy().
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  766): Killing 5545:com.sec.android.soagent/u0a37 (adj 15): empty for 1824s
I/SELinux ( 6324): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6324):  
I/SELinux ( 6324):  
I/SELinux ( 6324): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6324): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6324): >>>>> Normal User
E/dalvikvm( 6324): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6324): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  766): GC_EXPLICIT freed 1154K, 60% free 23751K/58056K, paused 5ms+20ms, total 246ms
D/TimaKeyStoreProvider( 6324): in addTimaSignatureService
D/PackageManager(  766): delete sourFile : 
D/TimaKeyStoreProvider( 6324): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6324): Added TimaKesytore provider
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6286): Shutting down VM
D/PackageManager(  766): delete native library directory: 
D/PackageManager(  766): return delete result to caller: 1123816784
D/PackageManager(  766): returnCode: 1
D/dalvikvm( 6286): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 3ms
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "sms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "smsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mmsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=6324, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 6324): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x424f5c60, skipping init
I/SecureStorage( 6324): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6324): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6324
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6324): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1259): onRestart, Launcher: 1113179936
D/Launcher( 1259): onStart, Launcher: 1113179936
D/Launcher.HomeView( 1259): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1451): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1451): [237392/5] SurfaceWidget drawing first frame
I/SecureStorage( 6324): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6324
I/SecureStorage(  299): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/SurfaceFlinger(  248): id=22 createSurf (720x1280),1 flag=4, Mauncher
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  766): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  766): clearDefaults: com.test.thalitest
D/InputReader(  766): Processing first event
W/ApplicationsProvider( 1410): Could not fetch usage stats
W/ApplicationsProvider( 1410): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1410): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1410): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1410): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1410): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1410): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1410): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
