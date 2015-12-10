#### Test 50650278c17c777_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5221): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5221):  
--------- beginning of /dev/log/system
I/ActivityManager(  793): Killing 3981:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
I/SELinux ( 5221): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5221):  
I/SELinux ( 5221):  
I/SELinux ( 5221): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5221): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5221): >>>>> Normal User
E/dalvikvm( 5221): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
,E/SELinux ( 5221): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  241): GC_EXPLICIT freed 46K, 49% free 9507K/18632K, paused 4ms+3ms, total 57ms
D/TimaKeyStoreProvider( 5221): in addTimaSignatureService
D/dalvikvm(  241): GC_EXPLICIT freed <1K, 49% free 9507K/18632K, paused 2ms+3ms, total 18ms
D/TimaKeyStoreProvider( 5221): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5221): Added TimaKesytore provider
D/dalvikvm(  241): GC_EXPLICIT freed <1K, 49% free 9507K/18632K, paused 2ms+3ms, total 19ms
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5221, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  221): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5221): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  221): Returning OperationFailed - no handler for errno 30
E/cutils  (  221): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5221): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  793): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  221): Returning OperationFailed - no handler for errno 30
I/SA      ( 4062): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4062): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4062): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4356): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2179): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/AndroidRuntime( 5240): 
D/AndroidRuntime( 5240): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5240): CheckJNI is OFF
D/AndroidRuntime( 5240): setted country_code = Poland
D/AndroidRuntime( 5240): setted countryiso_code = PL
D/AndroidRuntime( 5240): setted sales_code = XEO
D/AndroidRuntime( 5240): readGMSProperty: start
D/AndroidRuntime( 5240): readGMSProperty: already setted!!
D/AndroidRuntime( 5240): readGMSProperty: end
D/AndroidRuntime( 5240): addProductProperty: start
D/dalvikvm( 5240): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5240): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5240): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5240): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5240): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ContextImpl( 4712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5263): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5263):  
I/SELinux ( 5263): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5263):  
I/SELinux ( 5263):  
I/SELinux ( 5263): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5263): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5263): >>>>> Normal User
E/dalvikvm( 5263): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
I/ActivityManager(  793): Killing 3993:com.samsung.klmsagent/u0a18 (adj 15): empty #43
E/SELinux ( 5263): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/IcingCorporaProvider( 2179): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
D/TimaKeyStoreProvider( 5263): in addTimaSignatureService
D/TimaKeyStoreProvider( 5263): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5263): Added TimaKesytore provider
D/CapabilityManagerService New( 5263): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
E/memtrack( 5240): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5240): failed to load memtrack module: -2
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5263, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5276): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5276):  
I/ActivityManager(  793): Killing 4284:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/dalvikvm( 5240): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SELinux ( 5276): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5276):  
I/SELinux ( 5276):  
I/SELinux ( 5276): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5276): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5276): >>>>> Normal User
E/dalvikvm( 5276): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5276): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5276): in addTimaSignatureService
D/TimaKeyStoreProvider( 5276): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5276): Added TimaKesytore provider
D/AndroidRuntime( 5240): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  793): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  793): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  793): mDVFSHelper.acquire()
I/SELinux ( 5290): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5290):  
D/LockPatternUtils( 1072): isPcwEnable = null
D/AndroidRuntime( 5240): Shutting down VM
D/dalvikvm( 5240): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5276, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
E/SMD     (  234): DCD ON
I/SELinux ( 5290): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5290):  
I/SELinux ( 5290):  
I/SELinux ( 5290): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5290): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5290): >>>>> Normal User
E/dalvikvm( 5290): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5290): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5290): in addTimaSignatureService
D/TimaKeyStoreProvider( 5290): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5290): Added TimaKesytore provider
D/LockPatternUtils( 1072): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2113): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2113): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  240): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  240): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1265): destroyHardwareResources():1125589264
I/SurfaceFlinger(  240): id=8 Removed Mauncher (7/11)
I/SurfaceFlinger(  240): id=8 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1265): onTrimMemory. Level: 20
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5290, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5290, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5290): Binding Chromium to the background looper Looper (main, tid 1) {42243130}
I/chromium( 5290): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5290): Initializing chromium process, renderers=0
W/chromium( 5290): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5290): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5290): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5290): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5290): Remote Branch: 
I/Adreno-EGL( 5290): Local Patches: 
I/Adreno-EGL( 5290): Reconstruct Branch: 
,I/dalvikvm( 5290): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5290): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5290): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5290): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5290): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5290): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5290): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5290): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5290): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5290): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5290): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5290): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5290): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5290): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5290): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  240): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5290): EGLImpl-HWUI Protected EGL context created
I/SELinux ( 5332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5332):  
I/ActivityManager(  793): Killing 4007:com.sec.android.soagent/u0a37 (adj 15): empty #43
D/OpenGLRenderer( 5290): Enabling debug mode 0
W/AwContents( 5290): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
W/GAV2    ( 5276): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5332):  
I/SELinux ( 5332):  
I/SELinux ( 5332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5332): >>>>> Normal User
E/dalvikvm( 5332): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/CustomFrequencyManagerService(  793): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  793): mDVFSHelper.release()
D/CustomFrequencyManagerService(  793): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5332): in addTimaSignatureService
D/TimaKeyStoreProvider( 5332): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5332): Added TimaKesytore provider
D/PackageIntentReceiver( 5332): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5332): Not GearManger package! 
I/SELinux ( 5351): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5351):  
I/SELinux ( 5351): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5351):  
I/SELinux ( 5351):  
I/SELinux ( 5351): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5351): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5351): >>>>> Normal User
E/dalvikvm( 5351): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5351): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5351): in addTimaSignatureService
D/TimaKeyStoreProvider( 5351): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5351): Added TimaKesytore provider
D/MagazineService Version( 5351): Magazine-Channel: 13
D/MagazineService Version( 5351): Magazine-Provider: 13
D/MagazineService Version( 5351): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5351): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5351): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5351, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5351): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5367):  
D/MagazineService::MagazineService( 5351): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  793): Killing 4392:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5367):  
I/SELinux ( 5367):  
I/SELinux ( 5367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5367): >>>>> Normal User
E/dalvikvm( 5367): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
W/GAV2    ( 5276): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/SELinux ( 5367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  793): Killing 4407:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
D/TimaKeyStoreProvider( 5367): in addTimaSignatureService
D/TimaKeyStoreProvider( 5367): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5367): Added TimaKesytore provider
D/JsMessageQueue( 5290): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 5290): Trying to load lib /data/app-lib/com.test.thalitest-26/libjxcore.so 0x42569f10
D/dalvikvm( 5290): Added shared lib /data/app-lib/com.test.thalitest-26/libjxcore.so 0x42569f10
D/jxcore_app_log( 5290): JniHelper::setJavaVM(0x41701528), pthread_self() = 2032802976
D/JX-Cordova( 5290): jxcore cordova android initializing
I/dalvikvm( 5290): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5290): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5290): VFY: replacing opcode 0x6e at 0x0045
I/SELinux ( 5382): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5382):  
I/ActivityManager(  793): Killing 4419:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5382): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5382):  
I/SELinux ( 5382):  
,I/SELinux ( 5382): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5382): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5382): >>>>> Normal User
,E/dalvikvm( 5382): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5382): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5382): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5382): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5382): Added TimaKesytore provider
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5382, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5382): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5394): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5394):  
I/ActivityManager(  793): Killing 3590:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 5394): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5394):  
I/SELinux ( 5394):  
,I/SELinux ( 5394): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5394): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5394): >>>>> Normal User
,E/dalvikvm( 5394): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5394): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5394): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5394): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5394): Added TimaKesytore provider
,I/ActivityManager(  793): Killing 4447:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/Finsky  ( 3689): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/dalvikvm( 5290): GC_CONCURRENT freed 4925K, 32% free 12762K/18632K, paused 2ms+4ms, total 38ms
D/dalvikvm( 5290): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/dalvikvm( 5290): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1649): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1649): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1649): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1649): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1649): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1649): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1649): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1649): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1649): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1649): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1649): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1649): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1649): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService(  793): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  tag : ACTIVITY_RESUME_BOOSTER@9
D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1649): Submit a task: k
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1649): Processing package: com.test.thalitest
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,D/GassUtils( 1649): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1649): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1649): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1649): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1649): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
,W/dalvikvm( 1649): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1649): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1649): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1649): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1649): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1649): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1649): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1649): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5290): GC_FOR_ALLOC freed 4696K, 27% free 15765K/21428K, paused 33ms, total 33ms
,D/AmoledAdjustTimer(  793): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/dalvikvm( 1309): GC_EXPLICIT freed 880K, 42% free 10869K/18632K, paused 4ms+5ms, total 43ms
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1649): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 5290): GC_FOR_ALLOC freed 5048K, 31% free 16772K/24100K, paused 37ms, total 38ms
,I/dalvikvm-heap( 5290): Grow heap (frag case) to 21.645MB for 2459024-byte allocation
,D/dalvikvm( 5290): GC_FOR_ALLOC freed 3768K, 35% free 17453K/26504K, paused 35ms, total 37ms
,I/Icing   ( 1649): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
D/dalvikvm( 1649): GC_CONCURRENT freed 1862K, 34% free 12327K/18632K, paused 11ms+4ms, total 97ms
I/Icing   ( 1649): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
D/dalvikvm( 5290): GC_FOR_ALLOC freed 1223K, 35% free 17358K/26504K, paused 30ms, total 30ms
E/SMD     (  234): DCD ON
W/jxcore-log( 5290): Initializing JXcore engine
W/jxcore-log( 5290): JXcore engine is ready
W/jxcore-log( 5290): Starting JXcore engine
W/jxcore-log( 5290): Platform android
W/jxcore-log( 5290): 
W/jxcore-log( 5290): Process ARCH arm
W/jxcore-log( 5290): 
,I/jxcore-log( 5290): JXcore Cordova bridge is ready!
I/jxcore-log( 5290): 
,W/jxcore-log( 5290): JXcore engine is started
,I/chromium( 5290): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5290): Toggling radios to true
I/jxcore-log( 5290): 
,D/BluetoothAdapter( 5290): enable(): BT is already enabled..!
,I/WifiManager( 5290): packageName : com.test.thalitest
I/WifiManager( 5290): setWifiEnabled : true
,I/WifiService(  793): setWifiEnabled: true pid=5290, uid=10179
,W/WifiService(  793): Failed getting userId using ActivityManagerNative
W/WifiService(  793): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5290, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  793): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  793): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  793): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  793): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  793): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  793): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5290, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/WifiService(  793): disconnect: pid=5290, uid=10179
I/jxcore-log( 5290): Radios toggled
I/jxcore-log( 5290): 
I/wpa_supplicant( 1958): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1958): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1958): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1958): Cmd 35605 not handled
E/wpa_supplicant( 1958): Cmd 35605 not handled
I/wpa_supplicant( 1958): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,D/Tethering(  793): InitialState.processMessage what=4
,E/Tethering(  793): No numeric data
,D/Tethering(  793): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
I/ConnectivityService(  793): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  793): performPollLocked(flags=0x1)
,D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1958): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1958): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1958): First Scan Start
,I/wpa_supplicant( 1958): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  793): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  793): ignore requestNetworkTransitionWakelock airplane:true
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked() took 56ms
D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/WifiP2pService(  793): InactiveState{ what=143375 }
D/WifiP2pService(  793): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/CommandListener(  231): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  793): evaluateTrafficStatsPolling
D/ConnectivityService(  793): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  793): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  793): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  793): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  793): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  793): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1072): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1072): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  793): Attempting to switch to mobile
D/ConnectivityService(  793): Attempting to switch to BLUETOOTH_TETHER
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,I/wpa_supplicant( 1958): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1958): Skip scan - already scanning
,I/SELinux ( 5437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5437):  
D/STATUSBAR-IconMerger( 1072): checkOverflow(336), More:false, Req:false Child:2
,V/RouteController(  231): /system/bin/ip -6 route del default table 2 2>&1
,D/WifiP2pService(  793): InactiveState{ what=143375 }
,D/WifiP2pService(  793): P2pEnabledState{ what=143375 }
,V/RouteController(  231): RTNETLINK answers: No such process
I/SELinux ( 5437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5437):  
I/SELinux ( 5437):  
,I/SELinux ( 5437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/RouteController(  231): /system/bin/ip -6 rule del table 2 2>&1
E/SELinux ( 5437): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5437): >>>>> Normal User
,E/dalvikvm( 5437): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5437): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  231): RTNETLINK answers: No such file or directory
,D/CommandListener(  231): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  793): evaluateTrafficStatsPolling
,E/WifiStateMachine(  793): Error! unhandled message{ when=-92ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  793): Error! unhandled message{ when=-92ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService(  793): route cmd failed: 
W/NetworkManagementService(  793): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  793): '
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  793): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  793): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  793): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  231): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 5437): in addTimaSignatureService
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  793): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/TimaKeyStoreProvider( 5437): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5437): Added TimaKesytore provider
V/RouteController(  231): RTNETLINK answers: No such process
V/RouteController(  231): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  231): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  793): android_net_utils_resetConnections in env=0x7ab7c310 clazz=0x6b500001 iface=wlan0 mask=0x3
D/ConnectivityService(  793): resetConnections(wlan0, 3)
,V/NativeCrypto( 1309): Read error: ssl=0x73e0a170: I/O error during system call, Connection timed out
,V/NativeCrypto( 1309): SSL shutdown failed: ssl=0x73e0a170: I/O error during system call, Broken pipe
,V/AlarmManager(  793): waitForAlarm result :4
,V/AlarmManager(  793): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): updateIfacesLocked()
V/NetworkStats(  793): performPollLocked(flags=0x1)
V/NetworkStats(  793): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/ConnectivityService(  793): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked() took 24ms
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,I/System.out( 5437): Inside WakeupProvider
,I/System.out( 5437): Inside onCreate() of WakeupTriggerProvide
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  793): stay LED for fully charged
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1908): Disconnected process message: 10
I/VlingoApplication( 5437): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
D/VlingoApplication( 5437): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 5437): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(336), More:false, Req:false Child:2
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5437): initQueue()
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  793): Killing 4462:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 68438 latestRequest time : 1449746224864 current time : 1449746293302
,D/FactoryTest( 4778): Not factory mode
,D/FactoryTest( 4778): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4778): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4778): still no open session command from host, so toast
W/ContextImpl( 4778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  793): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  793): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  793): mDVFSHelper.acquire()
,D/LockPatternUtils( 1072): isPcwEnable = null
,D/LockPatternUtils( 1072): isPcwEnable = null
,E/MTPRx   ( 4778): started activity for popup
I/SQLiteSecureOpenHelper( 2113): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2113): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4778): PREF_DONT_ASK_AGAIN : false
,D/Tethering(  793): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy(  793): updateDataUsageMap
,D/Tethering(  793): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  793): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  793): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/LocSvc_java(  793): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  793): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  793): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5173): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5173): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5173): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5173): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5173): noConnectivity : true
,I/NetworkMonitor( 3923): type=WIFI subType= reason=null isConnected=false
,I/SELinux ( 5472): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5472):  
,D/dalvikvm(  793): GC_EXPLICIT freed 2725K, 60% free 23788K/58312K, paused 7ms+16ms, total 147ms
,I/SELinux ( 5472): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5472):  
I/SELinux ( 5472):  
,I/SELinux ( 5472): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5472): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5472): >>>>> Normal User
,E/dalvikvm( 5472): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5472): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SettingsReceiverActivity( 4778): dev.kiessupport is : TRUE
,D/TimaKeyStoreProvider( 5472): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5472): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5472): Added TimaKesytore provider
,I/GAV2    ( 5276): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 1958): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1958): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1958): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1958): Trying to associate with  'G700'
I/wpa_supplicant( 1958): Re-associate with C0.AA.48
,I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1958): Cmd 35609 not handled
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,I/SurfaceFlinger(  240): id=18 createSurf (1x1),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4778): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4778): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4778): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4778): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4778): Remote Branch: 
I/Adreno-EGL( 4778): Local Patches: 
I/Adreno-EGL( 4778): Reconstruct Branch: 
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5472, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  793): Killing 4493:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
I/HWUI    ( 4778): EGLImpl-HWUI Protected EGL context created
,E/wpa_supplicant( 1958): Cmd 35605 not handled
I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1958): Associated with C0.AA.48
I/wpa_supplicant( 1958): freq(2412) increment count 2
,I/wpa_supplicant( 1958): meet head of list.
E/wpa_supplicant( 1958): Cmd 35847 not handled
E/wpa_supplicant( 1958): Cmd 35848 not handled
E/wpa_supplicant( 1958): Cmd 35605 not handled
,I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1958): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1958): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,D/WifiNative(  793): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
D/Tethering(  793): interfaceLinkStateChanged wlan0, true
,D/Tethering(  793): interfaceStatusChanged wlan0, true
D/WifiP2pService(  793): InactiveState{ what=143375 }
,E/Tethering(  793): No numeric data
,D/Tethering(  793): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  793): interfaceLinkStateChanged wlan0, true
,D/Tethering(  793): interfaceStatusChanged wlan0, true
D/Tethering(  793): interfaceLinkStateChanged wlan0, true
,D/Tethering(  793): interfaceStatusChanged wlan0, true
D/Tethering(  793): interfaceLinkStateChanged wlan0, true
,D/Tethering(  793): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/WifiP2pService(  793): P2pEnabledState{ what=143375 }
I/ConnectivityService(  793): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  793): performPollLocked(flags=0x1)
,D/Tethering(  793): interfaceLinkStateChanged wlan0, true
,D/OpenGLRenderer( 4778): Enabling debug mode 0
,D/Tethering(  793): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked() took 33ms
,D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 5491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5491):  
,D/CustomFrequencyManagerService(  793): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  793): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  793): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/dalvikvm(  241): GC_EXPLICIT freed 43K, 49% free 9507K/18632K, paused 2ms+2ms, total 26ms
,D/dalvikvm(  241): GC_EXPLICIT freed <1K, 49% free 9507K/18632K, paused 1ms+3ms, total 18ms
I/SELinux ( 5491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5491):  
I/SELinux ( 5491):  
,I/SELinux ( 5491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5491): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5491): >>>>> Normal User
,E/dalvikvm( 5491): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5491): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  241): GC_EXPLICIT freed <1K, 49% free 9507K/18632K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 5491): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5491): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5491): Added TimaKesytore provider
,I/dhcpcd  ( 5497): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5497): bssid match
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5491, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  793): Killing 4510:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5510): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5510):  
,E/SMD     (  234): DCD ON
,I/SELinux ( 5510): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5510):  
I/SELinux ( 5510):  
,I/SELinux ( 5510): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5510): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5510): >>>>> Normal User
,E/dalvikvm( 5510): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5510): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5510): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5510): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5510): Added TimaKesytore provider
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5510, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5510): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5510): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449746294452
,I/KLMS-2.3.201 : ( 5510): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager(  793): Killing 1345:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 5522): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5522):  
,I/SELinux ( 5522): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5522):  
I/SELinux ( 5522):  
,I/SELinux ( 5522): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5522): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5522): >>>>> Normal User
,E/dalvikvm( 5522): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5522): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5522): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5522): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5522): Added TimaKesytore provider
,D/SO_AGENT( 5522): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5522): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5522, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4062): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4062): [BDLM] already registered in spp
,I/SA      ( 4062): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4062): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4062): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4062): [OR] == isSIMCardReady false ==
I/SA      ( 4062): [SCU] == networkStateCheck == false
,I/SA      ( 4062): [OR] onReceive END
I/ActivityManager(  793): Killing 4644:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1243): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1243): Phone number locator feature is dsiabled
,I/SELinux ( 5534): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5534):  
,I/SELinux ( 5534): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5534):  
I/SELinux ( 5534):  
,I/SELinux ( 5534): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5534): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5534): >>>>> Normal User
,E/dalvikvm( 5534): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
E/SELinux ( 5534): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5534): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5534): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5534): Added TimaKesytore provider
,I/sCloudBackupApp( 5534): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5534): Other Intent
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  793): Killing 4659:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5547): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5547):  
,I/SELinux ( 5547): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5547):  
I/SELinux ( 5547):  
,I/SELinux ( 5547): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5547): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5547): >>>>> Normal User
,E/dalvikvm( 5547): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5547): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5547): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5547): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5547): Added TimaKesytore provider
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5547, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  793): Killing 4680:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4117): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4117): getCountryCode(): countryCode = PL
D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4117): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4117): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4117): requestUpdateNewsWelcomeCard !!! no welcome card
D/CustomFrequencyManagerService(  793): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 793  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 5560): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5560):  
,I/SELinux ( 5560): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5560):  
I/SELinux ( 5560):  
,I/SELinux ( 5560): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5560): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5560): >>>>> Normal User
,E/dalvikvm( 5560): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5560): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5560): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5560): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5560): Added TimaKesytore provider
,E/cutils  (  221): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  221): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  221): Returning OperationFailed - no handler for errno 30
W/Vold    (  221): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5560): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  221): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  221): Returning OperationFailed - no handler for errno 30
,E/cutils  (  221): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  221): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5560): Binding Chromium to the main looper Looper (main, tid 1) {42245098}
,I/chromium( 5560): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5560): Initializing chromium process, renderers=0
,W/chromium( 5560): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5560): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5560): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5560): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5560): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5560): Remote Branch: 
I/Adreno-EGL( 5560): Local Patches: 
I/Adreno-EGL( 5560): Reconstruct Branch: 
,I/NSApplication( 5560): Starting up...
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5560, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  793): Killing 4728:com.google.android.talk/u0a105 (adj 15): empty #43
D/QuickConnect[1.1][2] ( 3348): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3348): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3348): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42577428
,I/SELinux ( 5595): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5595):  
,I/SELinux ( 5595): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5595):  
I/SELinux ( 5595):  
,I/SELinux ( 5595): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5595): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5595): >>>>> Normal User
,E/dalvikvm( 5595): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5595): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5595): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5595): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5595): Added TimaKesytore provider
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
I/ActivityManager(  793): Killing 3043:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5627): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5627):  
,I/SELinux ( 5633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5633):  
,I/SELinux ( 5627): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5627):  
I/SELinux ( 5627):  
,I/SELinux ( 5627): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5627): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5627): >>>>> Normal User
,E/dalvikvm( 5627): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5627): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/SELinux ( 5633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5633):  
I/SELinux ( 5633):  
,I/SELinux ( 5633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5633): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5633): >>>>> Normal User
,E/dalvikvm( 5633): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5633): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5627): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5627): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5627): Added TimaKesytore provider
W/ActivityManager(  793): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5633): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5633): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5633): Added TimaKesytore provider
,I/ActivityManager(  793): Killing 4815:com.sec.knox.bridge/1000 (adj 15): empty #43
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5627, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5633): onCreate
,D/BadgeProvider( 5633): DatabaseHelper
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5633, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5633): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  793): Killing 4831:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.Environment( 1649): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/BadgeProvider( 5633): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5633): sendNotify, [notify] : null
D/BadgeProvider( 5633): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5633): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5633): update, [UpdateCount] : 1
,D/Launcher.Model( 1265): reloadBadges entered.
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
,I/iu.UploadsManager( 1649): num queued entries: 0
,I/iu.UploadsManager( 1649): num updated entries: 0
,I/iu.SyncManager( 1649): NEXT; no task
,D/WifiP2pService(  793): InactiveState{ what=143375 }
,D/WifiP2pService(  793): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  793): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  793): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  793): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  793): evaluateTrafficStatsPolling
,D/WifiStateMachine(  793): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  793): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  793): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
I/WifiTrafficPoller(  793): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  793): mBoosterFLAG : 2
,I/WifiTrafficPoller(  793): current booster mode : BTCoexMode
D/ConnectivityService(  793): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  793): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  793): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1072): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1072): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
D/ConnectivityService(  793): handleConnectivityChange: setting default proxy info 
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,V/RouteController(  231): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,V/RouteController(  231): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  231): RTNETLINK answers: No such file or directory
,V/RouteController(  231): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
D/Toast   ( 1322):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1322): showing allowed
,V/RouteController(  231): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,V/RouteController(  231): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SurfaceFlinger(  240): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
,V/RouteController(  231): RTNETLINK answers: No such process
,V/RouteController(  231): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  793): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=793
,V/RouteController(  231): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  793): updateIfacesLocked()
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
V/NetworkStats(  793): performPollLocked(flags=0x1)
V/NetworkStats(  793): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked() took 19ms
,D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/Tethering(  793): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  793): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  793): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1072): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
,D/LocSvc_java(  793): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  793): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  793): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  793): SIOP:: AP = 330, Delta = 20
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3923): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5173): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5173): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5173): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5173): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/VacuumService( 1222): Vacuum at: now=1449746297093 tag=VacuumService
,I/KLMS-2.3.201 : ( 5510): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5510): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449746297171
,I/KLMS-2.3.201 : ( 5510): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2559): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/SO_AGENT( 5522): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/GalaxyFinderApplication( 2559): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5522): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 2559): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2559): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5697): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5697):  
,I/GallerySearchProvider( 2362): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5697): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5697):  
I/SELinux ( 5697):  
,I/SELinux ( 5697): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 5701): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5701):  
E/dalvikvm( 5697): >>>>> Normal User
,E/dalvikvm( 5697): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5697): in addTimaSignatureService
,E/SMD     (  234): DCD ON
I/SELinux ( 5701): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5701):  
I/SELinux ( 5701):  
,I/SELinux ( 5701): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5701): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5701): >>>>> Normal User
,E/dalvikvm( 5701): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5701): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5697): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5697): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5701): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5701): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5701): Added TimaKesytore provider
,V/KVNProvider( 5701): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5701): getFindoCursor query string : 
,V/KVNProvider( 5701): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4062): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4062): [BDLM] already registered in spp
I/SA      ( 4062): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4062): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4062): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4062): [OR] == isSIMCardReady false ==
I/SA      ( 4062): [SCU] == networkStateCheck == true
,I/SA      ( 4062): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4062): isChinaCountryCode : false
I/SA      ( 4062): [OR] == networkStateCheck true ==
,I/SA      ( 4062): [OR] GetMyCountryZoneTask
,I/SA      ( 4062): [OR] onReceive END
,I/SA      ( 4062): [SRS] prepareGetMyCountryZone
I/ActivityManager(  793): Killing 4685:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1243): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1243): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5534): Other Intent
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 4062): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4062): [SSP] query invoked
,D/Headlines( 4117): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4117): getCountryCode(): countryCode = PL
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4117): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4117): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4117): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SA      ( 4062): [TPMU] GetMccFromDB : null
I/SA      ( 4062): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4062): [TPM] isNoProxy(default) : true
,I/SA      ( 4062): [RC New] Execute method=[GET] start
,D/QuickConnect[1.1][2] ( 3348): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3348): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3348): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42577428
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4215): notifyNetworkActivated
,D/hcjo    ( 4215): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4215): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4215): exit::IDLE
,D/InitializeManagerStateMachine( 4215): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4215): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4215): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4215): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4215): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4215): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4215): entry::SUCCESS
,D/hcjo    ( 4215): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/iu.Environment( 1649): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/hcjo    ( 4215): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4215): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4215): exit::SUCCESS
,D/InitializeManagerStateMachine( 4215): entry::IDLE
,I/iu.UploadsManager( 1649): num queued entries: 0
,I/iu.UploadsManager( 1649): num updated entries: 0
,I/iu.SyncManager( 1649): NEXT; no task
,D/dalvikvm(  793): GC_EXPLICIT freed 2425K, 60% free 23676K/58312K, paused 7ms+13ms, total 142ms
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 10191 seconds from now (1449746298144)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1222): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1222): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,I/SA      ( 4062): [RC New] [v2liruge] api execute + 676
,I/SA      ( 4062): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4062): AsyncTask #2 calls detatch()
,D/LocationManagerService(  793): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SA      ( 4062): [TPMU] getNetworkMcc : 
,I/SA      ( 4062): [SCU] saveMccToPreferece Start
I/SA      ( 4062): [SCU] RegionMCC : 260
,I/SA      ( 4062): [SSP] query invoked
,I/SA      ( 4062): [TPMU] GetMccFromDB : null
I/SA      ( 4062): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4062): [SCU] saveMccToPreferece End
,I/SA      ( 4062): [RC New] executeRequest [v2liruge] end. 707
I/SA      ( 4062): [RC New] Execute end
I/dalvikvm( 1222): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1222): VFY: replacing opcode 0x6e at 0x003d
I/SA      ( 4062): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4062): [OR] GetMyCountryZoneTask Success
,I/System.out( 1222): Thread-110(HTTPLog):isShipBuild true
,I/System.out( 1222): Thread-110(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  793): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1072): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 1222): GC_CONCURRENT freed 1570K, 37% free 11874K/18632K, paused 4ms+8ms, total 48ms
,D/LocationManagerService(  793): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/WifiP2pStateTracker(  793): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  793): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  793):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  793): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  793): updateSourceRoutes : no source routing conditions
,E/WifiStateMachine(  793): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager(  793): Killing 4247:com.android.calendar/u0a142 (adj 15): empty #43
,I/SurfaceFlinger(  240): id=19 Removed Uoast (12/13)
,I/SurfaceFlinger(  240): id=19 Removed Uoast (-2/13)
,D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  793): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=793 (0x0)
D/PowerManagerService(  793): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=793, ws=WorkSource{1000}) (elapsedTime=3463)
,D/AmoledAdjustTimer(  793): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,I/GAV2    ( 5560): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  234): DCD ON
,I/HarmonyEASService(  793): Updating for all 1
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5173): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5173): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5173): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5173): ================================================
,I/CSTORAGE( 5173):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 5173): ================================================
,D/dalvikvm( 5173): No JNI_OnLoad found in /system/lib/libterrier.so 0x425713f0, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5173): [GetString-S]
I/terrier ( 5173): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5173): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5173): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5173): Loaded image: APP id = 3
,D/QSEECOMAPI: ( 5173): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5173): QSEECom_shutdown_app, app_id = 3
E/terrier ( 5173): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5173): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5173): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5173): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5173): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5173): [ensureRegistration] - No Samsung account
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 5290): Test app app.js loaded
I/jxcore-log( 5290): 
,I/chromium( 5290): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/AlarmManager(  793): waitForAlarm result :4
,V/AlarmManager(  793): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  793): stay LED for fully charged
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/UiModeManager(  793): mCoverManager.getCoverState() : true
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3689): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3689): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  234): DCD ON
,D/CaptivePortalTracker(  793): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  793): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  793): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  793): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  793): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  793): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/SSRMv2:SIOP(  793): SIOP:: AP = 320, Delta = -10
,D/CaptivePortalTracker(  793): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  793): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4215): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4215): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4215): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4215): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4215): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4215): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4215): entry::IDLE
,E/Watchdog(  793): !@Sync 4
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 294, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService(  793): [PWL] Off : 75s ago
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 17324 latestRequest time : 1449746297597 current time : 1449746314921
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = -20
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  793): !@Sync 5
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  793): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService(  793): [PWL] Off : 105s ago
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 47318 latestRequest time : 1449746297597 current time : 1449746344915
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 294, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  793): !@Sync 6
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 77314 latestRequest time : 1449746297597 current time : 1449746374911
,I/PowerManagerService(  793): [PWL] Off : 140s ago
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  793): !@Sync 7
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  793): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 107321 latestRequest time : 1449746297597 current time : 1449746404918
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 180s ago
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  793): !@Sync 8
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 137321 latestRequest time : 1449746297597 current time : 1449746434918
,D/Headlines( 4117): stop 
,D/Headlines( 4117): Breath.onDestroy : 
,I/ActivityManager(  793): Killing 4435:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 9
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  793): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  793): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/TimaService(  793): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  793): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  793): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  793): initializing...
,I/TLC_TIMA_PKM_initialize(  793): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  793): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  793): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  793): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  793): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  793): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  793): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  793): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  793): App is not loaded in QSEE
,D/QSEECOMAPI: (  793): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  793): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  793): Trustlet response is completed
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  793): !@Sync 10
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,D/AmoledAdjustTimer(  793): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  793): [PWL] Off : 275s ago
,D/AmoledAdjustTimer(  793): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :4
,V/AlarmManager(  793): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5849): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5849):  
,D/dalvikvm(  241): GC_EXPLICIT freed 43K, 49% free 9507K/18632K, paused 7ms+26ms, total 248ms
,D/dalvikvm(  241): GC_EXPLICIT freed <1K, 49% free 9507K/18632K, paused 19ms+18ms, total 169ms
,I/SELinux ( 5849): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5849):  
I/SELinux ( 5849):  
,I/SELinux ( 5849): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5849): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5849): >>>>> Normal User
,E/dalvikvm( 5849): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5849): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  241): GC_EXPLICIT freed <1K, 49% free 9507K/18632K, paused 5ms+10ms, total 70ms
,D/TimaKeyStoreProvider( 5849): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5849): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5849): Added TimaKesytore provider
,W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=5849, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  793): Killing 4629:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 11
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  793): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 12
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 330s ago
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1908): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1908): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1072): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5290): Toggling radios to false
I/jxcore-log( 5290): 
,D/BluetoothAdapterService(1113053912)( 1908): unRegister RemoteMessageListener
,D/HeadsetService( 1908): registerMessageListener
,D/HeadsetStateMachine( 1908): Disconnected process message: 80
,D/BluetoothAdapterState( 1908): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,I/BluetoothAdapterState( 1908): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1908): Bluetooth PBAP supproted is true
,I/WifiManager( 5290): packageName : com.test.thalitest
,D/HeadsetStateMachine( 1908): processUnRegisterMessageListener : 2
,D/BluetoothAdapterService( 1908): updateAdapterState state is 13
,I/WifiManager( 5290): setWifiEnabled : false
,I/WifiService(  793): setWifiEnabled: false pid=5290, uid=10179
,I/BluetoothPbapService( 1908): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 1908): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 1908): Autoconnection is available 
,E/bt-btif ( 1908): bta_jv_rfcomm_stop_server
,D/BluetoothAdapterService( 1908): updateAdapterState prevState = 12newState = 13
,W/InputMethodManagerService(  793): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  793): [BT Setting State] State =13
,D/PhoneApp( 1243): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,D/BluetoothAdapterService( 1908): terminating service from this receiver
,D/STATUSBAR-IconMerger( 1072): checkOverflow(336), More:false, Req:false Child:2
,I/wpa_supplicant( 1958): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1958): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1958): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings(  793): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QuickConnect[1.1][2] ( 3348): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
,I/WifiStateMachine(  793): ignore requestNetworkTransitionWakelock airplane:true
,I/jxcore-log( 5290): Radios toggled
I/jxcore-log( 5290): 
,D/WifiP2pService(  793): InactiveState{ what=143375 }
,W/ContextImpl( 1908): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/WifiP2pService(  793): P2pEnabledState{ what=143375 }
,D/GKI_LINUX( 1908): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BluetoothAdapterState( 1908): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,D/BluetoothAdapterState( 1908): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 1908): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 1908): bta_jv_rfcomm_stop_server
,E/BtOppRfcommListener( 1908): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 1908): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1908): cmd socket is not created
,D/btif_config_util( 1908): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BtOppRfcommListener( 1908): stopping Accept Thread
,I/BtOppRfcommListener( 1908): BluetoothSocket listen thread finished
,D/CommandListener(  231): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  793): evaluateTrafficStatsPolling
D/ConnectivityService(  793): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  793): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  793): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  793): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  793): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  793): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1072): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1072): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  793): Attempting to switch to mobile
D/ConnectivityService(  793): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
D/WifiP2pService(  793): InactiveState{ what=131204 }
D/WifiP2pService(  793): P2pEnabledState{ what=131204 }
E/WifiStateMachine(  793): Error! unhandled message{ when=-26ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  793): Error! unhandled message{ when=-32ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/IOP_DB_BT( 1908): db_close: nbr users 0
D/IOP_DB_BT( 1908): db_close: free database
D/BluetoothAdapterState( 1908): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 1908): isSecureModeOn:false
,W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1908): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 1908): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/HeadsetService( 1908): Received stop request...Stopping profile...
,D/QuickConnect[1.1][2] ( 3348): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,V/BluetoothEventManager( 1322): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 1908): Not skipping com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1908): Not skipping com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 1908): Not skipping com.android.bluetooth.hdp.HealthService
,W/ContextImpl( 1322): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1908): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1908): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 1908): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/WifiP2pService(  793): sending p2p connection changed broadcast: FAILED
D/BluetoothPbap( 1322): Proxy object disconnected
D/PbapServerProfile( 1322): Bluetooth service disconnected
D/HeadsetProfile( 1322): Bluetooth service disconnected
,D/BluetoothAdapterState( 1908): Stopping profile services that were post enabled
,D/QuickConnect[1.1][2] ( 3348): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
W/WifiP2pStateTracker(  793): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  793): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  793): onP2pDisconnected
D/IpRemoteDisplayController(  793): disconnectWfdBridgeServer
,D/IpRemoteDisplayController(  793): WfdBridgeServer is already null
D/DockEventReceiver( 1322): finishStartingService: stopping service
D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1908): Profile still running: com.android.bluetooth.hdp.HealthService
D/QuickConnect[1.1][2] ( 3348): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
W/BluetoothHeadsetServiceJni( 1908): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1908): Cleaning up Bluetooth Handsfree callback object
D/A2dpService( 1908): Received stop request...Stopping profile...
D/A2dpStateMachine( 1908): Exit Disconnected: -1
D/Avrcp   ( 1908): Unregistering previous receiver
D/MediaFocusControl(  793): <<< unregisterRemoteControlDisplay
D/BluetoothNotiBroadcastReceiver( 1322): onReceive
D/BluetoothA2dp(  793): Proxy object disconnected
D/BluetoothA2dp( 3348): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3348): A2dpProfile.onServiceConnected - Bluetooth service disconnected
D/HidService( 1908): Received stop request...Stopping profile...
D/HidService( 1908): Stopping Bluetooth HidService
D/BluetoothInputDevice( 3348): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3348): HidProfile.onServiceDisconnected - Bluetooth service disconnected
D/HealthService( 1908): Received stop request...Stopping profile...
D/GKI_LINUX( 1908): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/BluetoothA2dp( 2113): Proxy object disconnected
,D/PanService( 1908): Received stop request...Stopping profile...
,D/BluetoothA2dp( 1322): Proxy object disconnected
,V/RouteController(  231): /system/bin/ip -6 route del default table 2 2>&1
D/A2dpProfile( 1322): Bluetooth service disconnected
,D/BluetoothInputDevice( 1322): Proxy object disconnected
,D/HidProfile( 1322): Bluetooth service disconnected
,D/WifiP2pService(  793): sending p2p connection changed broadcast: DISCONNECTED
D/BluetoothPan(  793): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 1322): BluetoothPAN Proxy object disconnected
,D/PanProfile( 1322): Bluetooth service disconnected
,D/BluetoothMapService( 1908): Received stop request...Stopping profile...
,E/WifiStateMachine(  793): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 3348): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/QuickConnect[1.1][2] ( 3348): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/QuickConnect[1.1][2] ( 3348): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/QuickConnect[1.1][2] ( 3348): P2pHelper.removeP2pConfirm - skip: false
D/WifiP2pService(  793): P2pDisablingState
D/WifiP2pService(  793): P2pDisablingState{ what=139287 }
D/WifiP2pService(  793): DefaultState{ what=139287 }
D/WifiDisplayController(  793): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiP2pService(  793): P2pDisablingState{ what=147458 }
D/WifiDisplayController(  793): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  793): disconnect
D/WifiDisplayController(  793): updateConnection
D/WifiDisplayController(  793): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiP2pService(  793): p2p socket connection lost
D/WifiDisplayAdapter(  793): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  793): P2pDisabledState
,D/QuickConnect[1.1][2] ( 3348): CentralActionManager.removeHoldingIntentAll - all request done.
,D/QuickConnect[1.1][2] ( 3348): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3348): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,V/RouteController(  231): RTNETLINK answers: No such process
W/WifiP2pStateTracker(  793): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService(  793): P2pDisabledState{ what=139376 }
D/WifiP2pService(  793): DefaultState{ what=139376 }
E/WifiP2pService(  793): Unhandled message { what=139376 }
D/WifiDisplayController(  793): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  793): onP2pDisconnected
D/IpRemoteDisplayController(  793): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  793): WfdBridgeServer is already null
D/WifiP2pService(  793): P2pDisabledState{ what=139287 }
,V/RouteController(  231): /system/bin/ip -6 rule del table 2 2>&1
,D/BluetoothMap( 1322): Proxy object disconnected
,D/MapProfile( 1322): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1908): Profile still running: com.android.bluetooth.hdp.HealthService
,I/GKI_LINUX( 1908): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1908): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 1908): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1908): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1908): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 1908): Cleaning up Bluetooth GID callback object
D/WifiP2pService(  793): DefaultState{ what=139287 }
,D/WifiDisplayAdapter(  793): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 3348): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/QuickConnect[1.1][2] ( 3348): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1908): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 1908): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1908): Cleaning up Bluetooth Health object
,D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BtSettings.ProfileConfig( 1908): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1908): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1908): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1908): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 1908): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
D/BluetoothAdapterState( 1908): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,I/BluetoothAdapterState( 1908): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1908): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 1908): updateAdapterState state is 10
,D/BluetoothAdapterService( 1908): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 1908): Autoconnection is available 
D/BluetoothAdapterService( 1908): updateAdapterState prevState = 13newState = 10
,I/BluetoothAdapterState( 1908): Entering OffState
,V/RouteController(  231): RTNETLINK answers: No such file or directory
,D/CommandListener(  231): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  793): route cmd failed: 
W/NetworkManagementService(  793): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '60 route del src v6 2' failed with '400 60 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  793): '
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  793): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  793): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  793): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  793): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  793): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  231): /system/bin/ip -4 route del default table 2 2>&1
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
,D/BluetoothInputDevice( 3348): onBluetoothStateChange: up=false
,V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
,D/BluetoothA2dp( 2113): onBluetoothStateChange: up=false
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/Bluetoothsap( 1322): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1322): Unbinding service...
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,D/BluetoothA2dp( 1322): onBluetoothStateChange: up=false
I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
,D/BluetoothMap( 1322): onBluetoothStateChange: up=false
V/RouteController(  231): RTNETLINK answers: No such process
D/BluetoothPbap( 1322): onBluetoothStateChange: up=false
,V/RouteController(  231): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  231): /system/bin/ip route flush cached 2>&1
,I/SELinux ( 5916): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5916):  
,D/BluetoothInputDevice( 1322): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  793): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3348): onBluetoothStateChange: up=false
D/Bluetoothsap( 1322): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1322): Unbinding service...
,W/InputMethodManagerService(  793): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  793): [BT Setting State] State =10
,I/InputMethodManagerService(  793): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/WifiTrafficPoller(  793): mBoosterFLAG : 0
,I/WifiTrafficPoller(  793): current booster mode : FullMode
,D/PhoneApp( 1243): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,D/NetUtils(  793): android_net_utils_resetConnections in env=0x7ab7c310 clazz=0xa9600001 iface=wlan0 mask=0x3
,I/QuickConnect[1.1][2] ( 3348): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,D/ConnectivityService(  793): resetConnections(wlan0, 3)
D/WifiNative(  793): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1958): USE_NETWORK : USE_NETWORK OFF
,I/WifiTrafficPoller(  793): evaluateTrafficStatsPolling
,V/BluetoothEventManager( 1322): Received android.bluetooth.adapter.action.STATE_CHANGED
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,V/NativeCrypto( 1309): Read error: ssl=0x7c1133d8: I/O error during system call, Connection timed out
,D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1072): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1072): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1072): wifi: GONE sig=0 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=0 act=2130837934
D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=0 act=2130837934
,D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1072): wifi: GONE sig=0 act=2130837934
,D/SignalClusterView_dual( 1072): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1072): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,I/SELinux ( 5916): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5916):  
I/SELinux ( 5916):  
,I/SELinux ( 5916): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5916): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5916): >>>>> Normal User
,E/dalvikvm( 5916): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 5916): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,V/NativeCrypto( 1309): SSL shutdown failed: ssl=0x7c1133d8: I/O error during system call, Broken pipe
,D/TimaKeyStoreProvider( 5916): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5916): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5916): Added TimaKesytore provider
,E/WifiStateMachine(  793): Error! unhandled message{ when=-88ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  793): Error! unhandled message{ when=-88ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  793): Error! unhandled message{ when=-35ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  793): Error! unhandled message{ when=-36ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm(  793): GC_CONCURRENT freed 3527K, 60% free 23717K/58312K, paused 8ms+20ms, total 257ms
D/dalvikvm(  793): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm(  793): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm(  793): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/BluetoothTethering(  793): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  793): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/ConnectivityService(  793): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  793): updateIfacesLocked()
V/NetworkStats(  793): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/FileShare-Server( 5916): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5916): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() DISCONNECTED
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked() took 37ms
,W/ContextImpl( 1322): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/DockEventReceiver( 1322): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1322): onReceive
,D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 1958): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering(  793): interfaceLinkStateChanged p2p0, false
,D/Tethering(  793): interfaceStatusChanged p2p0, false
,I/ActivityManager(  793): Killing 4585:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
D/Tethering(  793): interfaceLinkStateChanged wlan0, true
D/Tethering(  793): interfaceStatusChanged wlan0, true
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
I/wpa_supplicant( 1958): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1958): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1958): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  793): InitialState.processMessage what=4
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
D/Tethering(  793): interfaceStatusChanged wlan0, false
,E/Tethering(  793): No numeric data
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,I/ConnectivityService(  793): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  793): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked(flags=0x1)
,I/knox    ( 3286): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3286): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3286): KNOXAgentService : onCreate()
,D/knox    ( 3286): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3286): KNOXAgentService. startJobThread() start
,D/knox    ( 3286): KNOXAgentService. JobThread()
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3286): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3286): KNOXAgentService. startJobThread() wait
D/knox    ( 3286): KNOXAgentService : onDestroy().
D/knox    ( 3286): ModuleBase.cancelAllAlarmManageModule()
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,V/NetworkStats(  793): performPollLocked() took 22ms
D/NtpTrustedTime(  793): currentTimeMillis() cache hit
D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,E/SMD     (  234): DCD ON
D/Tethering(  793): interfaceLinkStateChanged wlan0, false
,D/Tethering(  793): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1958): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiStateMachine(  793): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
W/Settings( 1222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/knox    ( 3286): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3286): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3286): KNOXAgentService : onCreate()
D/knox    ( 3286): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3286): KNOXAgentService. startJobThread() start
D/knox    ( 3286): KNOXAgentService. JobThread()
D/knox    ( 3286): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3286): KNOXAgentService. startJobThread() wait
D/knox    ( 3286): KNOXAgentService : onDestroy().
D/knox    ( 3286): ModuleBase.cancelAllAlarmManageModule()
,I/ApplicationPolicy(  793): updateDataUsageMap
,D/Tethering(  793): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  793): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  793): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  793): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  793): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  793): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  793): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1072): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1072): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1072): mSingleMobileLabelViews set as slot1`s
,I/NetworkMonitor( 3923): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5173): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5173): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5173): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5173): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5173): noConnectivity : true
,I/KLMS-2.3.201 : ( 5510): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/Netd    (  231): No subsystem found in netlink event
,D/NetlinkEvent(  231): Unexpected netlink message. type=0x11
I/KLMS-2.3.201 : ( 5510): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449746574033
I/KLMS-2.3.201 : ( 5510): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
D/Vpn     (  793): Interface removed : wlan0
D/Tethering(  793): interfaceRemoved wlan0
E/Tethering(  793): attempting to remove unknown iface (wlan0), ignoring
,D/SO_AGENT( 5522): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5522): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,W/Netd    (  231): No subsystem found in netlink event
D/NetlinkEvent(  231): Unexpected netlink message. type=0x11
,D/Vpn     (  793): Interface removed : p2p0
,D/Tethering(  793): interfaceRemoved p2p0
,E/Tethering(  793): attempting to remove unknown iface (p2p0), ignoring
,I/SA      ( 4062): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4062): [BDLM] already registered in spp
I/SA      ( 4062): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4062): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4062): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4062): [OR] == isSIMCardReady false ==
I/SA      ( 4062): [SCU] == networkStateCheck == false
,I/SA      ( 4062): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 1243): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1243): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5534): Other Intent
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4117): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4117): getCountryCode(): countryCode = PL
,D/Headlines( 4117): Breath.onCreate
,D/Headlines( 4117): Breath timer started. interval : 30000
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4117): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4117): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4117): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4117): requestUpdateNewsWelcomeCard !!! no welcome card
,V/AlarmManager(  793): waitForAlarm result :8
D/QuickConnect[1.1][2] ( 3348): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3348): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 3348): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42577428
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,D/RCPManagerService(  793): exchangeData() failure , invalid userId
,I/iu.Environment( 1649): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1649): num queued entries: 0
,I/iu.UploadsManager( 1649): num updated entries: 0
,I/iu.SyncManager( 1649): NEXT; no task
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 74 latestRequest time : 1449746574144 current time : 1449746574218
,D/WifiStateMachine(  793): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 13
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  793): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,I/ActivityManager(  793): Waited long enough for: ServiceRecord{439d3908 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  793): stay LED for fully charged
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 30051 latestRequest time : 1449746574144 current time : 1449746604197
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 14
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  234): DCD ON
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 390s ago
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 60046 latestRequest time : 1449746574144 current time : 1449746634190
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 15
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 90044 latestRequest time : 1449746574144 current time : 1449746664192
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 16
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 455s ago
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,D/Headlines( 4117): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4117): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4117): Breath 120044 latestRequest time : 1449746574144 current time : 1449746694188
,D/Headlines( 4117): stop 
,D/Headlines( 4117): Breath.onDestroy : 
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 17
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 18
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 19
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  793): [PWL] Off : 525s ago
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService(  793): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  793): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  793): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  793): !@Sync 20
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  793): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 21
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 600s ago
,V/AlarmManager(  793): waitForAlarm result :8
,I/SensorManagerA(  793): getReportingMode :: sensor.mType = 5
D/LightsService(  793): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  793): LightSensor setDelay = 200000000
,D/Sensors (  793): LightSensor setSensorDelay = 200000000
,D/Sensors (  793): Light sensor flush: not enabled 0
,D/Sensors (  793): LightSensor enable = 1
,D/Sensors (  793): LightSensor enableSensor = 1
,D/SensorManager(  793): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  793): LightSensor enable = 0
,D/Sensors (  793): LightSensor enableSensor = 0
,D/LightsService(  793): [SvcLED]  onSensorChanged::light value = 31
,D/SensorManager(  793): unregisterListener ::   
D/LightsService(  793): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 22
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 23
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  793): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  793): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
V/AlarmManager(  793): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  793): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 24
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService(  793): [PWL] Off : 680s ago
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 25
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/dalvikvm(  793): GC_CONCURRENT freed 3472K, 60% free 23717K/58312K, paused 30ms+59ms, total 652ms
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 26
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 27
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  793): [PWL] Off : 765s ago
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 28
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 29
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/TimaService(  793): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  793): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  793): TimaServiceHandler.handleMessage what =1
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  793): !@Sync 30
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 855s ago
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 31
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 32
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 33
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 950s ago
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 34
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 35
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  793): !@Sync 36
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 1050s ago
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  793): !@Sync 37
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  793): !@Sync 38
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  793): !@Sync 39
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/TimaService(  793): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  793): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  793): TimaServiceHandler.handleMessage what =1
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  793): !@Sync 40
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 1155s ago
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 41
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :8
,I/SensorManagerA(  793): getReportingMode :: sensor.mType = 5
,D/Sensors (  793): LightSensor setDelay = 200000000
,D/Sensors (  793): LightSensor setSensorDelay = 200000000
,D/Sensors (  793): Light sensor flush: not enabled 0
,D/Sensors (  793): LightSensor enable = 1
,D/Sensors (  793): LightSensor enableSensor = 1
,D/LightsService(  793): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager(  793): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  793): LightSensor enable = 0
,D/Sensors (  793): LightSensor enableSensor = 0
,D/LightsService(  793): [SvcLED]  onSensorChanged::light value = 31
,D/SensorManager(  793): unregisterListener ::   
D/LightsService(  793): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  793): stay LED for fully charged
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 42
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm(  793): GC_CONCURRENT freed 3458K, 60% free 23709K/58312K, paused 29ms+60ms, total 641ms
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  793): !@Sync 43
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  793): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  793): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
V/AlarmManager(  793): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  793): [PWL] Off : 1265s ago
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  793): !@Sync 44
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 45
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  793): !@Sync 46
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  793): !@Sync 47
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 1380s ago
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  793): !@Sync 48
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  793): !@Sync 49
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/TimaService(  793): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  793): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  793): TimaServiceHandler.handleMessage what =1
,E/SMD     (  234): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 50
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 51
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 1500s ago
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 52
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  234): DCD ON
D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/BatteryService(  793): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 53
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 54
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/BatteryService(  793): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 55
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,I/PowerManagerService(  793): [PWL] Off : 1625s ago
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 56
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 57
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,E/SMD     (  234): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 58
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/dalvikvm(  793): GC_CONCURRENT freed 3459K, 60% free 23737K/58312K, paused 22ms+60ms, total 648ms
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 59
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  793): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  793): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  793): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  793): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  793): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 60
,I/PowerManagerService(  793): [PWL] Off : 1755s ago
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 61
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,I/ProcessStatsService(  793): Prepared write state in 165ms
,I/ProcessStatsService(  793): Prepared write state in 158ms
,E/SMD     (  234): DCD ON
,I/ProcessStatsService(  793): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-57.bin
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,V/AlarmManager(  793): waitForAlarm result :4
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked(flags=0x3)
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/AlarmManager(  793): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
V/NetworkStats(  793): performPollLocked() took 198ms
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,D/NtpTrustedTime(  793): currentTimeMillis() cache hit
,I/SensorManagerA(  793): getReportingMode :: sensor.mType = 5
D/LightsService(  793): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  793): LightSensor setDelay = 200000000
,D/Sensors (  793): LightSensor setSensorDelay = 200000000
,D/Sensors (  793): Light sensor flush: not enabled 0
,D/Sensors (  793): LightSensor enable = 1
,D/Sensors (  793): LightSensor enableSensor = 1
,D/SensorManager(  793): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  793): LightSensor enable = 0
,D/Sensors (  793): LightSensor enableSensor = 0
,D/LightsService(  793): [SvcLED]  onSensorChanged::light value = 34
,D/SensorManager(  793): unregisterListener ::   
D/LightsService(  793): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1649): Aggregate from 1449746219386 (log), 1449746219386 (data)
,V/NativeCrypto( 1309): SSL shutdown failed: ssl=0x79f5cce8: I/O error during system call, Connection timed out
,E/Auth    ( 1309): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 62
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/Watchdog(  793): !@Sync 63
,V/AlarmManager(  793): waitForAlarm result :8
,V/AlarmManager(  793): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  793): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  793): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1072): handleTimeUpdate
V/AlarmManager(  793): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  793): stay LED for fully charged
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  234): DCD ON
,D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  793): mCoverManager.getCoverState() : true
,D/BatteryService(  793): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  234): DCD ON
,E/SMD     (  234): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  234): DCD ON
D/SSRMv2:SIOP(  793): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  793): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
D/BatteryService(  793): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  793): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  793): stay LED for fully charged
D/KeyguardUpdateMonitor( 1072): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1072): handleBatteryUpdate
D/UiModeManager(  793): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1072):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1072): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1072): checkOverflow(384), More:false, Req:false Child:2
E/SMD     (  234): DCD ON
D/AndroidRuntime( 6305): 
D/AndroidRuntime( 6305): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6305): CheckJNI is OFF
D/AndroidRuntime( 6305): setted country_code = Poland
D/AndroidRuntime( 6305): setted countryiso_code = PL
D/AndroidRuntime( 6305): setted sales_code = XEO
D/AndroidRuntime( 6305): readGMSProperty: start
D/AndroidRuntime( 6305): readGMSProperty: already setted!!
D/AndroidRuntime( 6305): readGMSProperty: end
D/AndroidRuntime( 6305): addProductProperty: start
D/dalvikvm( 6305): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6305): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6305): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6305): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6305): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6305): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6305): failed to load memtrack module: -2
D/dalvikvm( 6305): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6305): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  793): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  793): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  793): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  793): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  793): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  793): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  793): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  793): deletePackage- pkg:com.test.thalitest, edmuserId:-1
E/Watchdog(  793): !@Sync 64
D/PackageManager(  793): START PACKAGE DELETE: observer{1121790672}
D/PackageManager(  793): pkg{<packageName>}
D/PackageManager(  793): user{0}
D/PackageManager(  793): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  793): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy(  793): getApplicationUninstallationEnabled
D/ApplicationPolicy(  793): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  793): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  793): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  793): Killing 5290:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/ActivityManager(  793): Killing 5701:com.sec.android.app.voicenote/1000 (adj 15): empty for 1811s
I/ActivityManager(  793): Killing 5697:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1811s
I/ActivityManager(  793): Killing 5633:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1812s
I/ActivityManager(  793): Killing 5394:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1819s
I/ActivityManager(  793): Killing 5382:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1819s
I/ActivityManager(  793): Killing 5367:com.samsung.helphub/1000 (adj 15): empty for 1819s
I/ActivityManager(  793): Killing 5351:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1819s
I/ActivityManager(  793): Killing 5332:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1819s
I/ActivityManager(  793): Killing 5276:com.google.android.apps.docs/u0a90 (adj 15): empty for 1819s
I/ActivityManager(  793): Killing 5263:com.sec.android.service.cm/u0a78 (adj 15): empty for 1820s
I/ActivityManager(  793): Killing 4712:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1820s
I/ActivityManager(  793): Killing 4356:com.android.mms/u0a48 (adj 15): empty for 1820s
I/ActivityManager(  793): Killing 5221:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1820s
I/ActivityManager(  793): Killing 4264:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1821s
I/ActivityManager(  793): Killing 5185:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1821s
I/ActivityManager(  793): Killing 5157:com.android.musicfx/u0a24 (adj 15): empty for 1821s
I/ActivityManager(  793): Killing 5145:com.samsung.groupcast/u0a15 (adj 15): empty for 1822s
I/ActivityManager(  793): Killing 5130:com.google.android.partnersetup/u0a14 (adj 15): empty for 1822s
I/ActivityManager(  793): Killing 5116:com.sec.android.inputmethod/1000 (adj 15): empty for 1822s
I/ActivityManager(  793): Killing 5054:com.android.defcontainer/u0a6 (adj 15): empty for 1822s
I/WindowState(  793): WIN DEATH: Window{42f00a10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  240): id=17 Removed NainActivit (7/12)
I/SurfaceFlinger(  240): id=17 Removed NainActivit (-2/12)
I/SurfaceFlinger(  240): id=17 Removed NainActivit (-2/12)
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/CountryDetector(  793): No listener is left
W/PackageSettings(  793): Skipping PackageSetting{42548e10 com.example.hello/10180} due to missing metadata
D/PackageManager(  793): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1072): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  793): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 3348): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "sms"
I/FPMS_FingerprintManagerService( 1091): onReceive: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6331): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6331):  
D/dalvikvm( 1409): GC_EXPLICIT freed 4306K, 47% free 10027K/18632K, paused 8ms+5ms, total 91ms
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "smsto"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1649): GC_EXPLICIT freed 962K, 35% free 12272K/18632K, paused 8ms+9ms, total 120ms
W/SQLiteConnectionPool( 1649): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/SELinux ( 6331): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6331):  
I/SELinux ( 6331):  
I/SELinux ( 6331): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6331): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6331): >>>>> Normal User
E/dalvikvm( 6331): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6331): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "mms"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6331): in addTimaSignatureService
D/dalvikvm( 2179): GC_EXPLICIT freed 1014K, 40% free 11242K/18632K, paused 4ms+29ms, total 163ms
D/dalvikvm(  793): GC_EXPLICIT freed 2866K, 60% free 23787K/58312K, paused 7ms+19ms, total 174ms
D/TimaKeyStoreProvider( 6331): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6331): Added TimaKesytore provider
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "mmsto"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  793): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/RCPManagerService(  793): PackageReceiver onReceive()
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "smsto"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  793): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "mms"
I/SurfaceFlinger(  240): id=20 createSurf (1x1),2 flag=404, CatteryCove
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=6331, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "mmsto"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  793): Package has changed for user 0
D/EnterpriseDeviceManagerService(  793): Admin package name: com.google.android.gms
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6331): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6331): ELMEngine.ELMEngine( context ).
D/elm:14132( 6331): MDMBridge.setEnterpriseBridge()
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6331): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6331): ElmAgentService : onCreate()
D/elm:14132( 6331): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6331): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6331): MDMBridge.getInstance()
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6331): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6331): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6345): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6345):  
D/elm:14132( 6331): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6331): ElmAgentService : onDestroy().
I/SELinux ( 6345): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6345):  
I/SELinux ( 6345):  
I/SELinux ( 6345): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6345): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6345): >>>>> Normal User
E/dalvikvm( 6345): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6345): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6345): in addTimaSignatureService
D/TimaKeyStoreProvider( 6345): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6345): Added TimaKesytore provider
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  793): GC_EXPLICIT freed 977K, 60% free 23808K/58312K, paused 11ms+19ms, total 217ms
D/PackageManager(  793): delete sourFile : 
D/PackageManager(  793): delete native library directory: 
D/PackageManager(  793): return delete result to caller: 1121790672
D/AndroidRuntime( 6305): Shutting down VM
D/dalvikvm( 6305): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
D/PackageManager(  793): returnCode: 1
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "sms"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  793): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  793): removePackageParticipantsLocked: uid=10179 #1
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "smsto"
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "mms"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  793):   Action: "android.intent.action.SENDTO"
I/PackageManager(  793):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  793):   Scheme: "mmsto"
I/PackageManager(  793): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  793): Permission Denial: getCurrentUser() from pid=6345, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1265): onRestart, Launcher: 1113655728
D/Launcher( 1265): onStart, Launcher: 1113655728
D/Launcher.HomeView( 1265): onStart
D/dalvikvm( 6345): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4256ab70, skipping init
I/SecureStorage( 6345): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6345): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6345
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6345): [INFO]: SPID(0x00000000)SS Daemon is running
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1449): [237392/5] SurfaceWidget drawing first frame
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6345): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6345
I/SecureStorage(  293): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
I/SurfaceFlinger(  240): id=21 createSurf (720x1280),1 flag=4, Mauncher
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  793): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  793): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  793): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1072): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1072): handleKeyguardVisibilityChanged(1)
D/InputReader(  793): Processing first event
W/ApplicationsProvider( 1409): Could not fetch usage stats
W/ApplicationsProvider( 1409): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1409): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1409): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1409): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1409): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
