#### Test 50650278eab32a5_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5269): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5269):  
I/SELinux ( 5269): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5269):  
I/SELinux ( 5269):  
I/SELinux ( 5269): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5269): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5269): >>>>> Normal User
E/dalvikvm( 5269): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5269): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5269): in addTimaSignatureService
D/TimaKeyStoreProvider( 5269): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5269): Added TimaKesytore provider
,I/SELinux ( 5294): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5294):  
--------- beginning of /dev/log/system
I/ActivityManager(  756): Killing 4035:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  240): GC_EXPLICIT freed 46K, 49% free 9509K/18448K, paused 2ms+2ms, total 30ms
I/SELinux ( 5294): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5294):  
I/SELinux ( 5294):  
I/SELinux ( 5294): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5294): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5294): >>>>> Normal User
E/dalvikvm( 5294): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 49% free 9510K/18448K, paused 1ms+3ms, total 19ms
E/SELinux ( 5294): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 49% free 9510K/18448K, paused 2ms+2ms, total 19ms
D/TimaKeyStoreProvider( 5294): in addTimaSignatureService
D/TimaKeyStoreProvider( 5294): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5294): Added TimaKesytore provider
D/AndroidRuntime( 5291): 
D/AndroidRuntime( 5291): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5291): CheckJNI is OFF
D/AndroidRuntime( 5291): setted country_code = Poland
D/AndroidRuntime( 5291): setted countryiso_code = PL
D/AndroidRuntime( 5291): setted sales_code = XEO
D/AndroidRuntime( 5291): readGMSProperty: start
D/AndroidRuntime( 5291): readGMSProperty: already setted!!
D/AndroidRuntime( 5291): readGMSProperty: end
D/AndroidRuntime( 5291): addProductProperty: start
D/dalvikvm( 5291): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5291): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5291): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5291): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5291): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5294, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5294): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5294): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  756): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
I/SA      ( 4119): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4119): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4119): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
E/memtrack( 5291): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5291): failed to load memtrack module: -2
D/Mms/PackageInstallReceiver( 4424): loadAuthorityPref(): sEnableAuthority = true
D/dalvikvm( 5291): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/IcingCorporaProvider( 2181): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5328): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5328):  
D/AndroidRuntime( 5291): Calling main entry com.android.commands.am.Am
I/SELinux ( 5328): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5328):  
I/SELinux ( 5328):  
I/SELinux ( 5328): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5328): >>>>> Normal User
E/dalvikvm( 5328): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5328): in addTimaSignatureService
D/TimaKeyStoreProvider( 5328): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5328): Added TimaKesytore provider
V/ApplicationPolicy(  756): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/IcingCorporaProvider( 2181): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  756): mDVFSHelper.acquire()
I/SELinux ( 5343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5343):  
D/LockPatternUtils( 1068): isPcwEnable = null
D/AndroidRuntime( 5291): Shutting down VM
D/dalvikvm( 5291): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/SurfaceWidgetView( 1250): destroyHardwareResources():1131979624
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  239): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SELinux ( 5343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5343):  
I/SELinux ( 5343):  
I/SELinux ( 5343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5343): >>>>> Normal User
E/dalvikvm( 5343): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5343): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/ActivityManager(  756): Killing 4047:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SurfaceFlinger(  239): id=9 Removed Mauncher (7/11)
I/SurfaceFlinger(  239): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/Launcher( 1250): onTrimMemory. Level: 20
D/TimaKeyStoreProvider( 5343): in addTimaSignatureService
D/TimaKeyStoreProvider( 5343): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5343): Added TimaKesytore provider
D/LockPatternUtils( 1068): isPcwEnable = null
D/CapabilityManagerService New( 5328): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5328, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SQLiteSecureOpenHelper( 2117): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2117): getDatabaseLocked(b,b,pwd)...
I/SELinux ( 5356): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5356):  
I/ActivityManager(  756): Killing 4356:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5356):  
I/SELinux ( 5356):  
I/SELinux ( 5356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5356): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5356): >>>>> Normal User
E/dalvikvm( 5356): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5343, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
E/SELinux ( 5356): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5356): in addTimaSignatureService
D/TimaKeyStoreProvider( 5356): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5356): Added TimaKesytore provider
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5343, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5343): Binding Chromium to the background looper Looper (main, tid 1) {4285a1f8}
I/chromium( 5343): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5343): Initializing chromium process, renderers=0
W/chromium( 5343): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5343): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5343): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5343): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5343): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5343): Remote Branch: 
I/Adreno-EGL( 5343): Local Patches: 
I/Adreno-EGL( 5343): Reconstruct Branch: 
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/dalvikvm( 5343): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5343): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5343): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5343): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5343): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 5343): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 5343): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5343): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5343): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5343): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 5343): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 5343): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5343): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5343): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5343): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5343): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5343): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 5343): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 5343): CordovaWebView is running on device made by: samsung
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5356, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SurfaceFlinger(  239): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 5343): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 5343): Enabling debug mode 0
,W/AwContents( 5343): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  756): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@9
W/GAV2    ( 5356): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/JsMessageQueue( 5343): Set native->JS mode to OnlineEventsBridgeMode
I/SELinux ( 5404): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5404):  
I/SELinux ( 5404): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5404):  
I/SELinux ( 5404):  
I/SELinux ( 5404): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5404): >>>>> Normal User
E/dalvikvm( 5404): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5404): in addTimaSignatureService
D/TimaKeyStoreProvider( 5404): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5404): Added TimaKesytore provider
D/dalvikvm( 5343): Trying to load lib /data/app-lib/com.test.thalitest-20/libjxcore.so 0x42b80f68
D/PackageIntentReceiver( 5404): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5404): Not GearManger package! 
D/dalvikvm( 5343): Added shared lib /data/app-lib/com.test.thalitest-20/libjxcore.so 0x42b80f68
D/jxcore_app_log( 5343): JniHelper::setJavaVM(0x41e434f8), pthread_self() = 1925500232
D/JX-Cordova( 5343): jxcore cordova android initializing
I/SELinux ( 5420): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5420):  
I/dalvikvm( 5343): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5343): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5343): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  756): Killing 4060:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5420): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5420):  
I/SELinux ( 5420):  
I/SELinux ( 5420): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5420): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5420): >>>>> Normal User
E/dalvikvm( 5420): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5420): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5420): in addTimaSignatureService
D/TimaKeyStoreProvider( 5420): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5420): Added TimaKesytore provider
E/SMD     (  233): DCD ON
D/MagazineService Version( 5420): Magazine-Channel: 13
D/MagazineService Version( 5420): Magazine-Provider: 13
D/MagazineService Version( 5420): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5420): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5420): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5420, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5420): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5433): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5433):  
D/MagazineService::MagazineService( 5420): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  756): Killing 1336:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5433): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5433):  
I/SELinux ( 5433):  
I/SELinux ( 5433): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5433): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5433): >>>>> Normal User
E/dalvikvm( 5433): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5433): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5433): in addTimaSignatureService
D/TimaKeyStoreProvider( 5433): Cannot add TimaSignature Service, License check Failed
W/GAV2    ( 5356): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/ActivityThread( 5433): Added TimaKesytore provider
I/ActivityManager(  756): Killing 4460:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
D/dalvikvm( 5343): GC_CONCURRENT freed 4922K, 31% free 12768K/18448K, paused 2ms+2ms, total 31ms
D/dalvikvm( 5343): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 5343): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 5447): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5447):  
I/ActivityManager(  756): Killing 4475:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5447): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5447):  
I/SELinux ( 5447):  
,I/SELinux ( 5447): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5447): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5447): >>>>> Normal User
,E/dalvikvm( 5447): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5447): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5447): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5447): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5447): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5447, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5447): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5459): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5459):  
I/ActivityManager(  756): Killing 4490:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5459): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5459):  
I/SELinux ( 5459):  
,I/SELinux ( 5459): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5459): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5459): >>>>> Normal User
,E/dalvikvm( 5459): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5459): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5459): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5459): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5459): Added TimaKesytore provider
,D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@9
,I/ActivityManager(  756): Killing 3621:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3728): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1757): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1757): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1757): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1757): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x0053
,D/SSRMv2:SIOP(  756): SIOP:: AP = 310, Delta = 10
,I/dalvikvm( 1757): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1757): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1757): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1757): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1757): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1757): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1757): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1757): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1757): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1757): Submit a task: k
,D/dalvikvm( 5343): GC_FOR_ALLOC freed 4695K, 26% free 15768K/21240K, paused 36ms, total 42ms
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1757): Processing package: com.test.thalitest
,W/BaseAppContext( 1757): Using Auth Proxy for data requests.
,W/BaseAppContext( 1757): Using Auth Proxy for data requests.
,D/GassUtils( 1757): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1757): Found info for package com.test.thalitest in db.
,D/dalvikvm( 1308): GC_EXPLICIT freed 1418K, 41% free 10891K/18448K, paused 6ms+6ms, total 49ms
,I/PeopleContactsSync( 1757): Hangout changed: installed=true
,W/BaseAppContext( 1757): Using Auth Proxy for data requests.
,W/BaseAppContext( 1757): Using Auth Proxy for data requests.
,W/BaseAppContext( 1757): Using Auth Proxy for data requests.
,W/BaseAppContext( 1757): Using Auth Proxy for data requests.
,I/PeopleSync( 1757): requestContactSyncCleanup [5005f081]
,W/dalvikvm( 1757): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1757): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1757): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1757): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1757): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1757): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x000e
,I/dalvikvm( 1757): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1757): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1757): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1757): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1757): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1757): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1757): cleanUpNonGplusAccounts done.
,I/PeopleSync( 1757): requestContactSyncCleanup [5005f081]
,I/PeopleSync( 1757): onPerformSync() [5005f081]
,V/AlarmManager(  756): waitForAlarm result :8
,I/PeopleSync( 1757): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1757): Starting sync, feed=null [5005f081]
,I/PeopleContactsSync( 1757): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1757):   updateBabelActionMimeType
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
D/BatteryService(  756): stay LED for fully charged
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 5343): GC_FOR_ALLOC freed 5048K, 30% free 16775K/23912K, paused 40ms, total 41ms
,I/dalvikvm-heap( 5343): Grow heap (frag case) to 21.465MB for 2459024-byte allocation
,I/PeopleContactsSync( 1757): Updated babel action mime type
,I/PeopleContactsSync( 1757): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1757): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1757): Module APK com.google.android.play.games already loaded
,I/PeopleContactsSync( 1757): CP2 cleanup done, kept= duration=69 ms
,I/PeopleContactsSync( 1757): ===CP2 sync finished, success=true, time=175,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,D/dalvikvm( 1757): GC_CONCURRENT freed 1470K, 34% free 12287K/18448K, paused 6ms+8ms, total 99ms
,W/SQLiteConnectionPool( 1757): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm(  756): GC_EXPLICIT freed 2397K, 60% free 23641K/58176K, paused 7ms+14ms, total 151ms
,I/PeopleSync( 1757): ***Sync finished***, duration: 529 [5005f081]
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1757): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 1757): Processed handlePeopleChanged at 123669
,W/DataBroker( 1757): No player ID found and calling context is not the dest app
,I/dalvikvm( 1757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.isUninstalledAppPossiblyUpdating
,W/dalvikvm( 1757): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 1757): VFY: replacing opcode 0x6e at 0x000d
,I/PeopleSync( 1757): onPerformSync() [5005f081]
,D/dalvikvm( 5343): GC_FOR_ALLOC freed 3768K, 34% free 17455K/26316K, paused 40ms, total 40ms
,V/AlarmManager(  756): waitForAlarm result :8
,I/PeopleSync( 1757): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1757): Starting sync, feed=null [5005f081]
,I/PeopleContactsSync( 1757): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1757): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1757): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1757): CP2 cleanup done, kept= duration=25 ms
,I/PeopleContactsSync( 1757): ===CP2 sync finished, success=true, time=38,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/Icing   ( 1757): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/PeopleSync( 1757): ***Sync finished***, duration: 190 [5005f081]
,D/ChimeraCfgMgr( 1757): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1757): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 1757): Squelched handlePeopleChanged at 123927
,D/dalvikvm( 5343): GC_FOR_ALLOC freed 1224K, 35% free 17361K/26316K, paused 32ms, total 32ms
,I/Icing   ( 1757): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 5343): Initializing JXcore engine
,W/jxcore-log( 5343): JXcore engine is ready
,W/jxcore-log( 5343): Starting JXcore engine
,W/jxcore-log( 5343): Platform android
W/jxcore-log( 5343): 
,W/jxcore-log( 5343): Process ARCH arm
W/jxcore-log( 5343): 
,E/SMD     (  233): DCD ON
,I/jxcore-log( 5343): JXcore Cordova bridge is ready!
I/jxcore-log( 5343): 
,W/jxcore-log( 5343): JXcore engine is started
,I/chromium( 5343): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5343): Error!: missing ) after argument list
E/jxcore  ( 5343): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5343): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1068): isPcwEnable = null
I/ActivityManager(  756): Killing 4517:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  756): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/SurfaceWidgetView( 1250): destroyHardwareResources():1131979624
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  239): id=17 Removed NainActivit (7/11)
I/SurfaceFlinger(  239): id=17 Removed NainActivit (-2/11)
D/Launcher( 1250): onRestart, Launcher: 1120044992
D/Launcher( 1250): onStart, Launcher: 1120044992
,D/Launcher.HomeView( 1250): onStart
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1454): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  239): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  239): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1250): onStop
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  756): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  756): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 5356): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTest( 4835): Not factory mode
,D/FactoryTest( 4835): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4835): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4835): still no open session command from host, so toast
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  756): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  756): mDVFSHelper.acquire()
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/LockPatternUtils( 1068): isPcwEnable = null
,E/MTPRx   ( 4835): started activity for popup
,I/SQLiteSecureOpenHelper( 2117): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2117): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4835): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4835): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  239): id=20 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4835): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4835): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4835): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4835): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4835): Remote Branch: 
I/Adreno-EGL( 4835): Local Patches: 
I/Adreno-EGL( 4835): Reconstruct Branch: 
,I/HWUI    ( 4835): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4835): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  756): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  756): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,E/SMD     (  233): DCD ON
,D/CustomFrequencyManagerService(  756): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 756  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 310, Delta = 0
,I/HarmonyEASService(  756): Updating for all 1
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Headlines( 4176): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  756): stay LED for fully charged
D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/Headlines( 4176): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 4176): Breath 79267 latestRequest time : 1449668684324 current time : 1449668763591
,D/Finsky  ( 3728): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3728): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  756): !@Sync 4
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = -10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 105s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4176): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4176): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4176): Breath 94701 latestRequest time : 1449668684324 current time : 1449668779026
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  756): stay LED for fully charged
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/VacuumService( 1218): Vacuum at: now=1449668779989 tag=VacuumService
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PhenotypeConfigurator( 1218): Scheduling Phenotype for one-off execution 11654 seconds from now (1449668780432)
,D/GetConfigurationSnapshotOperation( 1218): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1218): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1218): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1218): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1218): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1218): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  756): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1218): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1218): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1218): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1218): Thread-110(HTTPLog):isShipBuild true
,I/System.out( 1218): Thread-110(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1218): GC_CONCURRENT freed 1494K, 36% free 11874K/18448K, paused 3ms+7ms, total 54ms
,E/SMD     (  233): DCD ON
,D/LocationManagerService(  756): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  756): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 5
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,D/Headlines( 4176): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4176): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4176): Breath 120036 latestRequest time : 1449668684324 current time : 1449668804360
,D/Headlines( 4176): stop 
,D/Headlines( 4176): Breath.onDestroy : 
,I/ActivityManager(  756): Killing 4536:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  756): [PWL] Off : 140s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 6
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService(  756): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 7
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,I/ClearcutLoggerApiImpl( 1757): disconnect managed GoogleApiClient
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 8
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 225s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 9
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm(  756): GC_CONCURRENT freed 3473K, 60% free 23620K/58172K, paused 20ms+41ms, total 437ms
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  756): initializing...
,I/TLC_TIMA_PKM_initialize(  756): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  756): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  756): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  756): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  756): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  756): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  756): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  756): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  756): App is not loaded in QSEE
,D/QSEECOMAPI: (  756): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  756): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  756): Trustlet response is completed
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  756): [PWL] Off : 275s ago
,I/PowerManagerService(  756): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  756): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  756): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=756, ws=null) (elapsedTime=2872)
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 10
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5624): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5624):  
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/SELinux ( 5624): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5624):  
I/SELinux ( 5624):  
,I/SELinux ( 5624): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5624): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5624): >>>>> Normal User
,E/dalvikvm( 5624): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5624): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5624): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5624): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5624): Added TimaKesytore provider
,W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=5624, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  756): Killing 4558:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,W/ProcessCpuTracker(  756): Skipping unknown process pid 5638
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 11
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  756): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,E/SMD     (  233): DCD ON
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 12
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 13
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  756): [PWL] Off : 390s ago
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,E/SMD     (  233): DCD ON
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 14
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 15
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  233): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  756): [PWL] Off : 455s ago
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 16
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 17
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 18
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 525s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 19
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,E/SMD     (  233): DCD ON
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 20
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  756): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 600s ago
,D/AmoledAdjustTimer(  756): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 21
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 22
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 23
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 680s ago
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager(  756): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 24
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 25
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  756): GC_CONCURRENT freed 3467K, 60% free 23605K/58172K, paused 35ms+36ms, total 444ms
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 26
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 765s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 27
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 28
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 29
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 855s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 30
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 31
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,I/SensorManagerA(  756): getReportingMode :: sensor.mType = 5
,D/LightsService(  756): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  756): LightSensor setDelay = 200000000
D/Sensors (  756): LightSensor setSensorDelay = 200000000
D/Sensors (  756): Light sensor flush: not enabled 0
D/Sensors (  756): LightSensor enable = 1
D/Sensors (  756): LightSensor enableSensor = 1
D/SensorManager(  756): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  756): LightSensor enable = 0
,D/Sensors (  756): LightSensor enableSensor = 0
,D/LightsService(  756): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  756): unregisterListener ::   
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/GCM     ( 1757): Message from null null
,E/GCM     ( 1757): Dropping message from null
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 32
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  756): [PWL] Off : 950s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): stay LED for fully charged
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 33
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 34
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 35
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1050s ago
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 36
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 37
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 38
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 39
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  756): !@Sync 40
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  756): GC_CONCURRENT freed 3436K, 60% free 23614K/58172K, paused 21ms+39ms, total 430ms
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 41
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 42
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  233): DCD ON
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  756): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 43
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 44
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 45
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 46
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1380s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 47
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 48
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  756): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 49
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  233): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 50
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1500s ago
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 51
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 52
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 53
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 54
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,I/PowerManagerService(  756): [PWL] Off : 1625s ago
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 55
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 56
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
E/SMD     (  233): DCD ON
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 57
,D/dalvikvm(  756): GC_CONCURRENT freed 3420K, 60% free 23639K/58168K, paused 19ms+39ms, total 431ms
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  756): !@Sync 58
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 59
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  756): [PWL] Off : 1755s ago
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService(  756): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  756): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  756): TimaServiceHandler.handleMessage what =1
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  756): Prepared write state in 187ms
,I/ProcessStatsService(  756): Prepared write state in 188ms
,I/ProcessStatsService(  756): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-43.bin
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  756): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  756): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 60
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 61
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,V/AlarmManager(  756): waitForAlarm result :4
,I/SensorManagerA(  756): getReportingMode :: sensor.mType = 5
,D/Sensors (  756): LightSensor setDelay = 200000000
,D/Sensors (  756): LightSensor setSensorDelay = 200000000
,D/LightsService(  756): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  756): Light sensor flush: not enabled 0
D/Sensors (  756): LightSensor enable = 1
D/Sensors (  756): LightSensor enableSensor = 1
D/SensorManager(  756): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
V/NetworkStats(  756): performPollLocked(flags=0x3)
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  756): stay LED for fully charged
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  756): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/LightsService(  756): [SvcLED]  onSensorChanged::light value = 0
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  756): LightSensor enable = 0
,D/Sensors (  756): LightSensor enableSensor = 0
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorManager(  756): unregisterListener ::   
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/LightsService(  756): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
V/NetworkStats(  756): performPollLocked() took 229ms
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,D/NtpTrustedTime(  756): currentTimeMillis() cache hit
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1757): Aggregate from 1449668677314 (log), 1449668677314 (data)
,D/ConnectivityService(  756): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,I/ActivityManager(  756): Killing 4642:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 3966:com.google.android.music:main/u0a122 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 4687:com.sec.phone/1001 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 4505:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 4313:com.android.calendar/u0a142 (adj 15): empty for 1806s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  756): Killing 4743:com.sec.providers.settingsearch/u0a160 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 4892:com.wssyncmldm/1000 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 4022:com.sec.android.diagmonagent/1000 (adj 15): empty for 1806s
,I/ActivityManager(  756): Killing 4864:com.sec.knox.bridge/1000 (adj 15): empty for 1807s
,I/ActivityManager(  756): Killing 3046:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1807s
,I/ActivityManager(  756): Killing 4787:com.google.android.talk/u0a105 (adj 15): empty for 1807s
,I/ActivityManager(  756): Killing 4731:com.android.providers.calendar/u0a44 (adj 15): empty for 1808s
,I/ActivityManager(  756): Killing 4715:com.sec.android.app.voicenote/1000 (adj 15): empty for 1808s
,I/ActivityManager(  756): Killing 4698:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1808s
,I/ActivityManager(  756): Killing 4574:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty for 1810s
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 62
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 63
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/BatteryService(  756): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  756): [PWL] Off : 1890s ago
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager(  756): waitForAlarm result :8
,V/AlarmManager(  756): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  756): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  756): <AppSync3 Whitelist>
,V/AlarmManager(  756): (AppSync) com.google.android.gms : 900(900)
,V/AlarmManager(  756): (AppSync) ### 1 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
I/ActivityManager(  756): Killing 4119:com.osp.app.signin/u0a43 (adj 15): empty for 1813s
,I/ActivityManager(  756): Killing 5294:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1813s
,I/ActivityManager(  756): Killing 4101:com.sec.spp.push/u0a38 (adj 15): empty for 1813s
,I/ActivityManager(  756): Killing 5269:com.policydm/1000 (adj 15): empty for 1813s
,I/ActivityManager(  756): Killing 4336:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1814s
,I/ActivityManager(  756): Killing 5250:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1814s
,I/ActivityManager(  756): Killing 5238:com.sec.pcw.device/1000 (adj 15): empty for 1814s
,I/ActivityManager(  756): Killing 5224:com.android.musicfx/u0a24 (adj 15): empty for 1814s
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  756): Killing 5209:com.samsung.groupcast/u0a15 (adj 15): empty for 1814s
,I/ActivityManager(  756): Killing 5194:com.google.android.partnersetup/u0a14 (adj 15): empty for 1814s
,I/ActivityManager(  756): Killing 5181:com.sec.android.inputmethod/1000 (adj 15): empty for 1815s
,I/ActivityManager(  756): Killing 5113:com.android.defcontainer/u0a6 (adj 15): empty for 1815s
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  756): !@Sync 64
,D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  756): stay LED for fully charged
,D/UiModeManager(  756): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP(  756): SIOP:: AP = 300, Delta = 0
E/SMD     (  233): DCD ON
D/BatteryService(  756): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
D/BatteryService(  756): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  756): stay LED for fully charged
D/UiModeManager(  756): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 1952): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1952): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  233): DCD ON
D/AmoledAdjustTimer(  756): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
D/AndroidRuntime( 6044): 
D/AndroidRuntime( 6044): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6044): CheckJNI is OFF
D/AndroidRuntime( 6044): setted country_code = Poland
D/AndroidRuntime( 6044): setted countryiso_code = PL
D/AndroidRuntime( 6044): setted sales_code = XEO
D/AndroidRuntime( 6044): readGMSProperty: start
D/AndroidRuntime( 6044): readGMSProperty: already setted!!
D/AndroidRuntime( 6044): readGMSProperty: end
D/AndroidRuntime( 6044): addProductProperty: start
D/dalvikvm( 6044): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6044): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6044): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6044): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6044): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6044): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6044): failed to load memtrack module: -2
D/dalvikvm( 6044): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6044): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  756): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  756): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  756): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  756): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  756): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  756): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  756): START PACKAGE DELETE: observer{1158886320}
D/PackageManager(  756): pkg{<packageName>}
D/PackageManager(  756): user{0}
D/PackageManager(  756): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  756): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  756): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  756): getApplicationUninstallationEnabled
D/ApplicationPolicy(  756): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  756): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  756): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  756): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  756): Killing 5343:com.test.thalitest/u0a179 (adj 11): stop com.test.thalitest
W/PackageSettings(  756): Skipping PackageSetting{43239a30 com.example.hello/10180} due to missing metadata
D/PackageManager(  756): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1412): GC_EXPLICIT freed 4347K, 46% free 10041K/18448K, paused 4ms+4ms, total 44ms
D/PackageManager(  756): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3384): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
I/SELinux ( 6068): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6068):  
D/dalvikvm( 1757): GC_EXPLICIT freed 1616K, 33% free 12387K/18448K, paused 5ms+6ms, total 154ms
D/dalvikvm( 2181): GC_EXPLICIT freed 1109K, 40% free 11251K/18448K, paused 14ms+5ms, total 138ms
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6068): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6068):  
I/SELinux ( 6068):  
I/SELinux ( 6068): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6068): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6068): >>>>> Normal User
E/dalvikvm( 6068): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6068): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  756): GC_EXPLICIT freed 3414K, 60% free 23714K/58168K, paused 6ms+14ms, total 166ms
D/dalvikvm(  756): WAIT_FOR_CONCURRENT_GC blocked 27ms
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mms"
D/TimaKeyStoreProvider( 6068): in addTimaSignatureService
D/TimaKeyStoreProvider( 6068): Cannot add TimaSignature Service, License check Failed
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread( 6068): Added TimaKesytore provider
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  756): PackageReceiver onReceive()
I/HarmonyEASService(  756): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "sms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=6068, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6068): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6068): ELMEngine.ELMEngine( context ).
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mms"
D/elm:14132( 6068): MDMBridge.setEnterpriseBridge()
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mmsto"
D/elm:14132( 6068): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6068): ElmAgentService : onCreate()
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 6068): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6068): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6068): MDMBridge.getInstance()
D/elm:14132( 6068): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6068): MDMBridge.getAllLicenseInfoFromSDK()
E/SMD     (  233): DCD ON
I/SELinux ( 6082): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6082):  
D/elm:14132( 6068): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/dalvikvm(  240): GC_EXPLICIT freed 43K, 49% free 9509K/18448K, paused 2ms+2ms, total 25ms
D/elm:14132( 6068): ElmAgentService : onDestroy().
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 49% free 9510K/18448K, paused 1ms+3ms, total 18ms
I/SELinux ( 6082): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6082):  
I/SELinux ( 6082):  
I/SELinux ( 6082): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6082): >>>>> Normal User
E/dalvikvm( 6082): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  756): removePackageParticipantsLocked: uid=10179 #1
D/dalvikvm(  240): GC_EXPLICIT freed <1K, 49% free 9510K/18448K, paused 2ms+3ms, total 19ms
D/TimaKeyStoreProvider( 6082): in addTimaSignatureService
D/TimaKeyStoreProvider( 6082): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6082): Added TimaKesytore provider
D/dalvikvm(  756): GC_EXPLICIT freed 1174K, 60% free 23601K/58168K, paused 5ms+20ms, total 305ms
D/PackageManager(  756): delete sourFile : 
W/ActivityManager(  756): Permission Denial: getCurrentUser() from pid=6082, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/EnterpriseDeviceManagerService(  756): Package has changed for user 0
D/EnterpriseDeviceManagerService(  756): Admin package name: com.google.android.gms
D/PackageManager(  756): delete native library directory: 
D/PackageManager(  756): return delete result to caller: 1158886320
D/AndroidRuntime( 6044): Shutting down VM
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
D/dalvikvm( 6044): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "sms"
D/PackageManager(  756): returnCode: 1
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "smsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mms"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  756):   Action: "android.intent.action.SENDTO"
I/PackageManager(  756):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  756):   Scheme: "mmsto"
I/PackageManager(  756): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6082): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42b8aac0, skipping init
I/SecureStorage( 6082): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6082): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  291): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6082
I/SecureStorage(  291): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6082): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 6082): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  291): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6082
I/SecureStorage(  291): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  756): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  756): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  756): clearDefaults: com.test.thalitest
D/InputReader(  756): Processing first event
W/ApplicationsProvider( 1412): Could not fetch usage stats
W/ApplicationsProvider( 1412): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1412): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1412): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1412): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1412): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
