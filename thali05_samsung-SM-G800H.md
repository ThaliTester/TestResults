#### Test 52383621d5a0cb8_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5269): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5269):  
,--------- beginning of /dev/log/system
I/ActivityManager(  778): Killing 4010:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  250): GC_EXPLICIT freed 46K, 51% free 9507K/19196K, paused 2ms+3ms, total 32ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19196K, paused 1ms+2ms, total 18ms
I/SELinux ( 5269): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5269):  
I/SELinux ( 5269):  
I/SELinux ( 5269): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5269): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5269): >>>>> Normal User
E/dalvikvm( 5269): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5269): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19196K, paused 2ms+3ms, total 18ms
D/TimaKeyStoreProvider( 5269): in addTimaSignatureService
D/TimaKeyStoreProvider( 5269): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5269): Added TimaKesytore provider
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5269, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager(  778): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5269): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
I/SA      ( 4081): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4081): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4081): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/AndroidRuntime( 5282): 
D/AndroidRuntime( 5282): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5282): CheckJNI is OFF
D/AndroidRuntime( 5282): setted country_code = Poland
D/AndroidRuntime( 5282): setted countryiso_code = PL
D/Mms/PackageInstallReceiver( 4394): loadAuthorityPref(): sEnableAuthority = true
D/AndroidRuntime( 5282): setted sales_code = XEO
D/AndroidRuntime( 5282): readGMSProperty: start
D/AndroidRuntime( 5282): readGMSProperty: already setted!!
D/AndroidRuntime( 5282): readGMSProperty: end
D/AndroidRuntime( 5282): addProductProperty: start
D/dalvikvm( 5282): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5282): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5282): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5282): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5282): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/IcingCorporaProvider( 2169): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4747): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5305): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5305):  
I/ActivityManager(  778): Killing 4024:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 5305): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5305):  
I/SELinux ( 5305):  
I/SELinux ( 5305): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5305): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5305): >>>>> Normal User
E/dalvikvm( 5305): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5305): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5305): in addTimaSignatureService
D/TimaKeyStoreProvider( 5305): Cannot add TimaSignature Service, License check Failed
E/memtrack( 5282): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5282): failed to load memtrack module: -2
D/ActivityThread( 5305): Added TimaKesytore provider
D/dalvikvm( 2169): GC_CONCURRENT freed 1867K, 39% free 11871K/19196K, paused 4ms+5ms, total 133ms
D/dalvikvm( 2169): WAIT_FOR_CONCURRENT_GC blocked 54ms
D/dalvikvm( 5282): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/CapabilityManagerService New( 5305): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5305, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/IcingCorporaProvider( 2169): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
I/SELinux ( 5317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5317):  
I/ActivityManager(  778): Killing 4320:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/AndroidRuntime( 5282): Calling main entry com.android.commands.am.Am
I/SELinux ( 5317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5317):  
I/SELinux ( 5317):  
I/SELinux ( 5317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5317): >>>>> Normal User
E/dalvikvm( 5317): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5317): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5317): in addTimaSignatureService
D/TimaKeyStoreProvider( 5317): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5317): Added TimaKesytore provider
V/ApplicationPolicy(  778): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  778): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  778): mDVFSHelper.acquire()
I/SELinux ( 5333): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5333):  
D/LockPatternUtils( 1071): isPcwEnable = null
D/AndroidRuntime( 5282): Shutting down VM
D/dalvikvm( 5282): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 5333): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5333):  
I/SELinux ( 5333):  
I/SELinux ( 5333): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5333): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5333): >>>>> Normal User
E/dalvikvm( 5333): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5333): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5333): in addTimaSignatureService
D/TimaKeyStoreProvider( 5333): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5333): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtils( 1071): isPcwEnable = null
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1254): destroyHardwareResources():1134683920
I/SQLiteSecureOpenHelper( 2125): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2125): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  249): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
D/Launcher( 1254): onTrimMemory. Level: 20
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5317, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5333, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5333, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5333): Binding Chromium to the background looper Looper (main, tid 1) {42aef2e0}
I/chromium( 5333): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5333): Initializing chromium process, renderers=0
W/chromium( 5333): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5333): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5333): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5333): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5333): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5333): Remote Branch: 
I/Adreno-EGL( 5333): Local Patches: 
I/Adreno-EGL( 5333): Reconstruct Branch: 
,I/dalvikvm( 5333): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5333): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5333): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5333): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5333): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5333): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5333): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5333): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5333): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5333): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5333): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5333): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5333): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5333): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5333): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5333): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5333): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5333): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5333): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5333): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5333): Enabling debug mode 0
W/AwContents( 5333): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  778): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  778): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  778): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  pkgName : ACTIVITY_RESUME_BOOSTER@9
W/GAV2    ( 5317): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5379):  
I/SELinux ( 5379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5379):  
I/SELinux ( 5379):  
I/SELinux ( 5379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5379): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5379): >>>>> Normal User
E/dalvikvm( 5379): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5379): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5379): in addTimaSignatureService
D/TimaKeyStoreProvider( 5379): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5379): Added TimaKesytore provider
W/ProcessCpuTracker(  778): Skipping unknown process pid 5397
D/JsMessageQueue( 5333): Set native->JS mode to OnlineEventsBridgeMode
D/PackageIntentReceiver( 5379): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5379): Not GearManger package! 
I/SELinux ( 5398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5398):  
I/ActivityManager(  778): Killing 4037:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5398):  
I/SELinux ( 5398):  
I/SELinux ( 5398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5398): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5398): >>>>> Normal User
E/dalvikvm( 5398): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5398): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5398): in addTimaSignatureService
D/TimaKeyStoreProvider( 5398): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5398): Added TimaKesytore provider
D/dalvikvm( 5333): Trying to load lib /data/app-lib/com.test.thalitest-4/libjxcore.so 0x42e15f78
D/dalvikvm( 5333): Added shared lib /data/app-lib/com.test.thalitest-4/libjxcore.so 0x42e15f78
D/jxcore_app_log( 5333): JniHelper::setJavaVM(0x4201c4f8), pthread_self() = 2033243384
D/JX-Cordova( 5333): jxcore cordova android initializing
I/dalvikvm( 5333): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 5333): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5333): VFY: replacing opcode 0x6e at 0x0045
D/MagazineService Version( 5398): Magazine-Channel: 13
D/MagazineService Version( 5398): Magazine-Provider: 13
D/MagazineService Version( 5398): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5398): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5398): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5398, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5398): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5411): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5411):  
D/MagazineService::MagazineService( 5398): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  778): Killing 4429:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5411): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5411):  
I/SELinux ( 5411):  
I/SELinux ( 5411): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5411): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5411): >>>>> Normal User
E/dalvikvm( 5411): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5411): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5317): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/TimaKeyStoreProvider( 5411): in addTimaSignatureService
I/ActivityManager(  778): Killing 4444:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
D/TimaKeyStoreProvider( 5411): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5411): Added TimaKesytore provider
I/SELinux ( 5425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5425):  
I/ActivityManager(  778): Killing 4456:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5425):  
I/SELinux ( 5425):  
,I/SELinux ( 5425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5425): >>>>> Normal User
,E/dalvikvm( 5425): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5425): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5425): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5425): Added TimaKesytore provider
,D/dalvikvm( 5333): GC_CONCURRENT freed 4926K, 34% free 12762K/19196K, paused 3ms+4ms, total 40ms
,D/dalvikvm( 5333): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 5333): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5425, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5425): Package not found : com.sec.android.app.kidshome
D/AmoledAdjustTimer(  778): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/SELinux ( 5437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5437):  
,I/ActivityManager(  778): Killing 3619:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 5437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5437):  
I/SELinux ( 5437):  
,I/SELinux ( 5437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5437): >>>>> Normal User
,E/dalvikvm( 5437): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5437): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5437): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5437): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5437): Added TimaKesytore provider
,I/ActivityManager(  778): Killing 4483:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Finsky  ( 3729): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1643): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/CustomFrequencyManagerService(  778): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  243): DCD ON
,D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1643): Submit a task: h
,I/PeopleContactsSync( 1643): CP2 sync disabled
,D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/h       ( 1643): Processing package: com.test.thalitest
,D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,I/dalvikvm( 1643): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1643): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1643): VFY: replacing opcode 0x6e at 0x000e
D/GassUtils( 1643): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/h       ( 1643): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,D/dalvikvm( 5333): GC_FOR_ALLOC freed 4769K, 29% free 15759K/22056K, paused 34ms, total 35ms
,D/dalvikvm( 5333): GC_FOR_ALLOC freed 4947K, 32% free 17001K/24784K, paused 37ms, total 37ms
,I/dalvikvm-heap( 5333): Grow heap (frag case) to 22.469MB for 2511452-byte allocation
,D/dalvikvm( 5333): GC_FOR_ALLOC freed 3465K, 34% free 18036K/27240K, paused 37ms, total 39ms
,D/dalvikvm( 5333): GC_FOR_ALLOC freed 1050K, 34% free 18159K/27240K, paused 33ms, total 35ms
,W/jxcore-log( 5333): Initializing JXcore engine
,W/jxcore-log( 5333): JXcore engine is ready
,W/jxcore-log( 5333): Starting JXcore engine
,W/jxcore-log( 5333): Platform android
W/jxcore-log( 5333): 
,W/jxcore-log( 5333): Process ARCH arm
W/jxcore-log( 5333): 
,V/AlarmManager(  778): waitForAlarm result :4
V/AlarmManager(  778): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/VacuumService( 1316): Vacuum at: now=1449056528314 tag=VacuumService
,I/jxcore-log( 5333): JXcore Cordova bridge is ready!
I/jxcore-log( 5333): 
,W/jxcore-log( 5333): JXcore engine is started
,I/chromium( 5333): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FactoryTest( 4813): Not factory mode
,D/FactoryTest( 4813): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4813): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4813): still no open session command from host, so toast
W/ContextImpl( 4813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  778): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  778): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  778): mDVFSHelper.acquire()
,D/LockPatternUtils( 1071): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2125): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2125): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtils( 1071): isPcwEnable = null
,E/MTPRx   ( 4813): started activity for popup
,E/jxcore  ( 5333): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 5333): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 5333): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  778): Killing 4500:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/SettingsReceiverActivity( 4813): PREF_DONT_ASK_AGAIN : false
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/SettingsReceiverActivity( 4813): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4813): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4813): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4813): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4813): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4813): Remote Branch: 
I/Adreno-EGL( 4813): Local Patches: 
I/Adreno-EGL( 4813): Reconstruct Branch: 
,I/HWUI    ( 4813): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4813): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,E/SMD     (  243): DCD ON
,D/SurfaceWidgetView( 1254): destroyHardwareResources():1134683920
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
D/Launcher( 1254): onRestart, Launcher: 1122748024
D/Launcher( 1254): onStart, Launcher: 1122748024
,D/Launcher.HomeView( 1254): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/Launcher.HomeView( 1254): onStop
,D/SurfaceWidget.Renderer( 1454): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=19 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  778): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  778): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  778): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  778): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1071): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1071): handleKeyguardVisibilityChanged(1)
,I/GAV2    ( 5317): Thread[GAThread,5,main]: No campaign data found.
,D/CustomFrequencyManagerService(  778): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 778  tag : ACTIVITY_RESUME_BOOSTER@9
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
D/BatteryService(  778): stay LED for fully charged
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/UiModeManager(  778): mCoverManager.getCoverState() : true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  778): SIOP:: AP = 320, Delta = 10
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,I/HarmonyEASService(  778): Updating for all 1
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  778): waitForAlarm result :4
,V/AlarmManager(  778): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 310, Delta = -10
,D/Finsky  ( 3729): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3729): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  778): !@Sync 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  778): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,D/Headlines( 4143): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4143): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4143): Breath 90050 latestRequest time : 1449056459877 current time : 1449056549927
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  778): stay LED for fully charged
D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/UiModeManager(  778): mCoverManager.getCoverState() : true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = -10
,E/SMD     (  243): DCD ON
,D/dalvikvm(  778): GC_EXPLICIT freed 3050K, 60% free 23636K/58580K, paused 25ms+23ms, total 615ms
,D/AmoledAdjustTimer(  778): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  778): !@Sync 5
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  778): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,D/Headlines( 4143): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4143): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4143): Breath 120045 latestRequest time : 1449056459877 current time : 1449056579922
,D/Headlines( 4143): stop 
,D/Headlines( 4143): Breath.onDestroy : 
,I/ActivityManager(  778): Killing 4529:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  778): stay LED for fully charged
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 293, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  778): !@Sync 6
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 140s ago
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  778): !@Sync 7
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 180s ago
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  778): !@Sync 8
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  778): !@Sync 9
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  778): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService(  778): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  778): TimaServiceHandler.handleMessage what =1
,D/TimaService(  778): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  778): initializing...
,I/TLC_TIMA_PKM_initialize(  778): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  778): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  778): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  778): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  778): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  778): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  778): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  778): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  778): App is not loaded in QSEE
,D/QSEECOMAPI: (  778): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  778): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  778): Trustlet response is completed
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  778): !@Sync 10
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 275s ago
,V/AlarmManager(  778): waitForAlarm result :4
,V/AlarmManager(  778): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5544): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5544):  
,D/AmoledAdjustTimer(  778): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,I/SELinux ( 5544): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5544):  
I/SELinux ( 5544):  
,I/SELinux ( 5544): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5544): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5544): >>>>> Normal User
,E/dalvikvm( 5544): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5544): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5544): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5544): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5544): Added TimaKesytore provider
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=5544, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  778): Killing 4545:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 11
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 12
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/BatteryService(  778): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 330s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 13
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 14
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 390s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 15
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
V/AlarmManager(  778): waitForAlarm result :8
V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 16
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 455s ago
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 17
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 18
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 19
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 525s ago
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/dalvikvm(  778): GC_CONCURRENT freed 3633K, 60% free 23461K/58580K, paused 23ms+47ms, total 509ms
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService(  778): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  778): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  778): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  778): !@Sync 20
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,W/ContextImpl(  778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 21
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 600s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 22
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  243): DCD ON
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 23
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  778): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  778): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
V/AlarmManager(  778): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 24
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 680s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 25
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 26
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 27
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 765s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 28
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 29
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/TimaService(  778): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  778): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  778): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  778): !@Sync 30
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 855s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 31
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :4
,I/SensorManagerA(  778): getReportingMode :: sensor.mType = 5
,D/Sensors (  778): LightSensor setDelay = 200000000
,D/LightsService(  778): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  778): LightSensor setSensorDelay = 200000000
D/Sensors (  778): Light sensor flush: not enabled 0
D/Sensors (  778): LightSensor enable = 1
D/Sensors (  778): LightSensor enableSensor = 1
,D/SensorManager(  778): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  778): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  778): LightSensor enable = 0
,D/Sensors (  778): LightSensor enableSensor = 0
,D/SensorManager(  778): unregisterListener ::   
D/LightsService(  778): [SvcLED]  onSensorChanged::light value = 28
D/LightsService(  778): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,I/GCM     ( 1643): Message from null null
,E/GCM     ( 1643): Dropping message from null
,I/GCM     ( 1643): Message from null null
,E/GCM     ( 1643): Dropping message from null
,D/UdcCache:FPQuery( 1643): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1316): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1316): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1643): GC_CONCURRENT freed 1407K, 37% free 12243K/19196K, paused 6ms+12ms, total 85ms
,D/dalvikvm( 1643): WAIT_FOR_CONCURRENT_GC blocked 42ms
,W/SQLiteConnectionPool( 1643): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ConnectivityService(  778): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1071): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,W/Uploader( 1316):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1316): GC_CONCURRENT freed 1850K, 42% free 11162K/19196K, paused 4ms+6ms, total 69ms
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  778): !@Sync 32
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/dalvikvm(  778): GC_CONCURRENT freed 3410K, 60% free 23472K/58580K, paused 19ms+75ms, total 474ms
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): stay LED for fully charged
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/Watchdog(  778): !@Sync 33
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 950s ago
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/Watchdog(  778): !@Sync 34
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/Watchdog(  778): !@Sync 35
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/Watchdog(  778): !@Sync 36
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/AmoledAdjustTimer(  778): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 1050s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  778): !@Sync 37
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  778): !@Sync 38
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  778): !@Sync 39
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/TimaService(  778): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  778): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  778): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,D/TimaService(  778): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/Watchdog(  778): !@Sync 40
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 1155s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,E/Watchdog(  778): !@Sync 41
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 42
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 43
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  778): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  778): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
V/AlarmManager(  778): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  778): [PWL] Off : 1265s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 44
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 45
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 46
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 47
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 1380s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  778): GC_CONCURRENT freed 3437K, 60% free 23433K/58580K, paused 48ms+46ms, total 561ms
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 48
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 49
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  778): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  778): TimaServiceHandler.handleMessage what =1
,D/TimaService(  778): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 50
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 51
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 1500s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 52
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 53
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 54
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 55
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 1625s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 56
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 57
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 58
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 59
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/TimaService(  778): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  778): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  778): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  778): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  778): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 60
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  778): [PWL] Off : 1755s ago
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  778): !@Sync 61
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  778): Prepared write state in 141ms
,I/ProcessStatsService(  778): Prepared write state in 102ms
,E/SMD     (  243): DCD ON
,I/ProcessStatsService(  778): Pruning old procstats: /data/system/procstats/state-2015-12-01-15-16-41.bin
,V/AlarmManager(  778): waitForAlarm result :4
,I/SensorManagerA(  778): getReportingMode :: sensor.mType = 5
,D/Sensors (  778): LightSensor setDelay = 200000000
,D/Sensors (  778): LightSensor setSensorDelay = 200000000
,D/LightsService(  778): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  778): Light sensor flush: not enabled 0
D/Sensors (  778): LightSensor enable = 1
D/Sensors (  778): LightSensor enableSensor = 1
D/SensorManager(  778): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime(  778): currentTimeMillis() cache hit
V/NetworkStats(  778): performPollLocked(flags=0x3)
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): stay LED for fully charged
,V/AlarmManager(  778): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  778): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  778): [SvcLED]  onSensorChanged::light value = 28
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/Sensors (  778): LightSensor enable = 0
D/Sensors (  778): LightSensor enableSensor = 0
,D/SensorManager(  778): unregisterListener ::   
D/LightsService(  778): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/NtpTrustedTime(  778): currentTimeMillis() cache hit
V/NetworkStats(  778): performPollLocked() took 224ms
,D/NtpTrustedTime(  778): currentTimeMillis() cache hit
,D/NtpTrustedTime(  778): currentTimeMillis() cache hit
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,D/dalvikvm(  778): GC_CONCURRENT freed 3338K, 60% free 23477K/58580K, paused 34ms+16ms, total 335ms
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1643): Aggregate from 1449055858625 (log), 1449055858625 (data)
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1316): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1316): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2: email) -> status: null)
,I/GLSUser ( 1316): [GLSUser] Extracting token using key: Auth
,W/GLSUser ( 1316): [GLSUser] Permission for com.google.android.gms to access oauth2: email will be managed locally.
,D/ConnectivityService(  778): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1071): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1071): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1071): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/ActivityManager(  778): Killing 4722:com.sec.android.app.voicenote/1000 (adj 15): empty for 1800s
,I/ActivityManager(  778): Killing 4687:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1801s
,I/ActivityManager(  778): Killing 1349:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1802s
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  778): !@Sync 62
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/UiModeManager(  778): mCoverManager.getCoverState() : true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1934): Disconnected process message: 10
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/Watchdog(  778): !@Sync 63
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  778): waitForAlarm result :8
,V/AlarmManager(  778): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  778): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  778): <AppSync3 Whitelist>
,V/AlarmManager(  778): (AppSync) com.google.android.gms : 900(900)
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1071): handleTimeUpdate
V/AlarmManager(  778): (AppSync) ### 1 added ###
,I/ActivityManager(  778): Killing 4857:com.sec.knox.bridge/1000 (adj 15): empty for 1839s
,I/ActivityManager(  778): Killing 3046:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1839s
,I/ActivityManager(  778): Killing 4711:com.sec.providers.settingsearch/u0a160 (adj 15): empty for 1839s
,I/ActivityManager(  778): Killing 4763:com.google.android.talk/u0a105 (adj 15): empty for 1839s
,I/ActivityManager(  778): Killing 4622:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1850s
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  778): Killing 3940:com.google.android.music:main/u0a122 (adj 15): empty for 1850s
,I/ActivityManager(  778): Killing 4664:com.sec.phone/1001 (adj 15): empty for 1850s
,I/ActivityManager(  778): Killing 4471:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1850s
,I/ActivityManager(  778): Killing 4704:com.android.providers.calendar/u0a44 (adj 15): empty for 1850s
,I/ActivityManager(  778): Killing 4275:com.android.calendar/u0a142 (adj 15): empty for 1850s
,I/ActivityManager(  778): Killing 4880:com.wssyncmldm/1000 (adj 15): empty for 1850s
,I/ActivityManager(  778): Killing 3994:com.sec.android.diagmonagent/1000 (adj 15): empty for 1850s
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/BatteryService(  778): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  778): stay LED for fully charged
,D/UiModeManager(  778): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1934): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
,W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  243): DCD ON
D/SSRMv2:SIOP(  778): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  778): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
E/SMD     (  243): DCD ON
D/BatteryService(  778): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
D/BatteryService(  778): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  778): stay LED for fully charged
D/UiModeManager(  778): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1071): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1071): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1071):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1071): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1071): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1934): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1934): Disconnected process message: 10
W/ctxmgr  ( 1222): [PowerConnectionState]Got same value as before for power connection (Plug state: 2 BatteryLevel: 1.0)
D/AndroidRuntime( 5983): 
D/AndroidRuntime( 5983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5983): CheckJNI is OFF
D/AndroidRuntime( 5983): setted country_code = Poland
D/AndroidRuntime( 5983): setted countryiso_code = PL
D/AndroidRuntime( 5983): setted sales_code = XEO
D/AndroidRuntime( 5983): readGMSProperty: start
D/AndroidRuntime( 5983): readGMSProperty: already setted!!
D/AndroidRuntime( 5983): readGMSProperty: end
D/AndroidRuntime( 5983): addProductProperty: start
D/dalvikvm( 5983): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5983): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5983): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5983): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5983): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/Watchdog(  778): !@Sync 64
E/memtrack( 5983): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5983): failed to load memtrack module: -2
D/dalvikvm( 5983): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5983): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  778): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  778): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  778): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  778): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  778): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  778): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  778): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  778): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  778): getApplicationUninstallationEnabled
D/ApplicationPolicy(  778): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  778): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  778): START PACKAGE DELETE: observer{1126258704}
D/PackageManager(  778): pkg{<packageName>}
D/PackageManager(  778): user{0}
D/PackageManager(  778): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  778): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  778): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  778): Killing 5333:com.test.thalitest/u0a179 (adj 11): stop com.test.thalitest
I/ActivityManager(  778): Killing 5269:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1820s
I/ActivityManager(  778): Killing 4067:com.sec.spp.push/u0a38 (adj 15): empty for 1820s
I/ActivityManager(  778): Killing 5244:com.policydm/1000 (adj 15): empty for 1820s
I/ActivityManager(  778): Killing 4300:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1820s
I/ActivityManager(  778): Killing 5227:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1820s
I/ActivityManager(  778): Killing 5215:com.sec.pcw.device/1000 (adj 15): empty for 1821s
I/ActivityManager(  778): Killing 5198:com.android.musicfx/u0a24 (adj 15): empty for 1821s
I/ActivityManager(  778): Killing 5185:com.samsung.groupcast/u0a15 (adj 15): empty for 1821s
I/ActivityManager(  778): Killing 5169:com.google.android.partnersetup/u0a14 (adj 15): empty for 1821s
I/ActivityManager(  778): Killing 5153:com.sec.android.inputmethod/1000 (adj 15): empty for 1821s
I/ActivityManager(  778): Killing 5121:com.android.defcontainer/u0a6 (adj 15): empty for 1822s
D/PackageManager(  778): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2169): GC_EXPLICIT freed 548K, 40% free 11540K/19196K, paused 3ms+4ms, total 37ms
D/PackageManager(  778): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1071): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3379): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader(  778): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1414): GC_EXPLICIT freed 4371K, 48% free 10023K/19196K, paused 3ms+3ms, total 54ms
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "sms"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/FPMS_FingerprintManagerService( 1090): onReceive: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "smsto"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "mms"
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 6009): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6009):  
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "mmsto"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "sms"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6009): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6009):  
I/SELinux ( 6009):  
I/SELinux ( 6009): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6009): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6009): >>>>> Normal User
E/dalvikvm( 6009): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6009): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6009): in addTimaSignatureService
D/TimaKeyStoreProvider( 6009): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6009): Added TimaKesytore provider
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "smsto"
D/dalvikvm(  778): GC_EXPLICIT freed 2185K, 60% free 23505K/58580K, paused 6ms+15ms, total 169ms
D/dalvikvm(  778): WAIT_FOR_CONCURRENT_GC blocked 149ms
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "mms"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "mmsto"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  778): PackageReceiver onReceive()
D/EnterpriseDeviceManagerService(  778): Package has changed for user 0
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=6009, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/EnterpriseDeviceManagerService(  778): Admin package name: com.google.android.gms
I/HarmonyEASService(  778): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132( 6009): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6009): ELMEngine.ELMEngine( context ).
D/elm:14132( 6009): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6009): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6009): ElmAgentService : onCreate()
D/elm:14132( 6009): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6009): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6009): MDMBridge.getInstance()
D/elm:14132( 6009): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6009): MDMBridge.getAllLicenseInfoFromSDK()
D/dalvikvm(  250): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/SELinux ( 6022): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6022):  
D/dalvikvm(  250): GC_EXPLICIT freed 43K, 51% free 9507K/19196K, paused 2ms+3ms, total 25ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19196K, paused 2ms+3ms, total 19ms
D/elm:14132( 6009): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux ( 6022): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6022):  
I/SELinux ( 6022):  
I/SELinux ( 6022): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6022): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6022): >>>>> Normal User
E/dalvikvm( 6022): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6022): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19196K, paused 1ms+2ms, total 19ms
D/TimaKeyStoreProvider( 6022): in addTimaSignatureService
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6022): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6022): Added TimaKesytore provider
D/elm:14132( 6009): ElmAgentService : onDestroy().
I/ActivityManager(  778): Killing 4081:com.osp.app.signin/u0a43 (adj 15): empty for 1820s
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  778): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  778): removePackageParticipantsLocked: uid=10179 #1
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  778): Permission Denial: getCurrentUser() from pid=6022, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm(  778): GC_EXPLICIT freed 1058K, 60% free 23490K/58580K, paused 6ms+22ms, total 281ms
D/PackageManager(  778): delete sourFile : 
D/dalvikvm( 6022): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42e1e920, skipping init
I/SecureStorage( 6022): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6022): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  304): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6022
I/SecureStorage(  304): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6022): [INFO]: SPID(0x00000000)SS Daemon is running
D/PackageManager(  778): delete native library directory: 
D/PackageManager(  778): return delete result to caller: 1126258704
D/AndroidRuntime( 5983): Shutting down VM
I/SecureStorage( 6022): [INFO]: SPID(0x00000000)Processing data
D/dalvikvm( 5983): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+1ms, total 2ms
I/SecureStorage(  304): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6022
I/SecureStorage(  304): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/PackageManager(  778): returnCode: 1
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "sms"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "smsto"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "mms"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  778):   Action: "android.intent.action.SENDTO"
I/PackageManager(  778):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  778):   Scheme: "mmsto"
I/PackageManager(  778): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  778): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  778): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  778): clearDefaults: com.test.thalitest
E/SMD     (  243): DCD ON
D/InputReader(  778): Processing first event
I/EventHub(  778): Removing device '/dev/input/event1' due to inotify event
I/EventHub(  778): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=217 classes=0x94
I/InputReader(  778): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  778): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  778): MultiTouchMotionAccumulator: initial slot number is -1
D/InputDispatcher(  778): setInputDispatchMode: enabled=0, frozen=1
I/ActivityManager(  778): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
I/SurfaceFlinger(  249): id=20 createSurf (720x1280),2 flag=404, TcreenshotS
D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (342 us)
D/Mms/MmsApp( 4394): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/Mms/MmsApp( 4394): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
W/ApplicationsProvider( 1414): Could not fetch usage stats
W/ApplicationsProvider( 1414): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1414): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1414): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1414): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1414): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1414): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1414): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1414): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1414): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
