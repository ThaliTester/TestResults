#### Test 52320939cae1769_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5192): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5192):  
--------- beginning of /dev/log/system
I/ActivityManager(  746): Killing 3943:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  249): GC_EXPLICIT freed 45K, 50% free 9506K/19000K, paused 2ms+3ms, total 31ms
I/SELinux ( 5192): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5192):  
I/SELinux ( 5192):  
I/SELinux ( 5192): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5192): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5192): >>>>> Normal User
E/dalvikvm( 5192): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5192): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 5192): in addTimaSignatureService
D/TimaKeyStoreProvider( 5192): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5192): Added TimaKesytore provider
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 2ms+3ms, total 19ms
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5192, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5192): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5192): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  746): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
I/SA      ( 4016): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4016): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4016): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4333): loadAuthorityPref(): sEnableAuthority = true
D/AndroidRuntime( 5209): 
D/AndroidRuntime( 5209): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5209): CheckJNI is OFF
D/AndroidRuntime( 5209): setted country_code = Poland
D/AndroidRuntime( 5209): setted countryiso_code = PL
D/AndroidRuntime( 5209): setted sales_code = XEO
D/AndroidRuntime( 5209): readGMSProperty: start
D/AndroidRuntime( 5209): readGMSProperty: already setted!!
D/AndroidRuntime( 5209): readGMSProperty: end
D/AndroidRuntime( 5209): addProductProperty: start
E/SMD     (  242): DCD ON
I/IcingCorporaProvider( 2184): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/dalvikvm( 5209): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5209): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5209): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5209): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5209): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ContextImpl( 4659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5231): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5231):  
I/SELinux ( 5231): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5231):  
I/SELinux ( 5231):  
I/SELinux ( 5231): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5231): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5231): >>>>> Normal User
E/dalvikvm( 5231): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5231): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/ActivityManager(  746): Killing 3955:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/TimaKeyStoreProvider( 5231): in addTimaSignatureService
D/TimaKeyStoreProvider( 5231): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5231): Added TimaKesytore provider
I/IcingCorporaProvider( 2184): UpdateCorporaTask done [took 147 ms] updated apps [took 147 ms] 
E/memtrack( 5209): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5209): failed to load memtrack module: -2
D/CapabilityManagerService New( 5231): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5231, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 5244): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5244):  
D/dalvikvm( 5209): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/ActivityManager(  746): Killing 4254:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 5244): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5244):  
I/SELinux ( 5244):  
I/SELinux ( 5244): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5244): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5244): >>>>> Normal User
E/dalvikvm( 5244): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5244): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5244): in addTimaSignatureService
D/AndroidRuntime( 5209): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 5244): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5244): Added TimaKesytore provider
V/ApplicationPolicy(  746): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  746): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  746): mDVFSHelper.acquire()
I/SELinux ( 5259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5259):  
D/LockPatternUtils( 1068): isPcwEnable = null
D/AndroidRuntime( 5209): Shutting down VM
D/dalvikvm( 5209): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SELinux ( 5259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5259):  
I/SELinux ( 5259):  
I/SELinux ( 5259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5259): >>>>> Normal User
E/dalvikvm( 5259): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5259): in addTimaSignatureService
D/TimaKeyStoreProvider( 5259): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5259): Added TimaKesytore provider
D/LockPatternUtils( 1068): isPcwEnable = null
D/SurfaceWidgetView( 1260): destroyHardwareResources():1133986304
I/SQLiteSecureOpenHelper( 2095): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2095): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5244, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/SurfaceFlinger(  248): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1260): onTrimMemory. Level: 20
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5259, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5259, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5259): Binding Chromium to the background looper Looper (main, tid 1) {42a45150}
I/chromium( 5259): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5259): Initializing chromium process, renderers=0
W/chromium( 5259): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5259): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5259): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5259): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5259): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5259): Remote Branch: 
I/Adreno-EGL( 5259): Local Patches: 
I/Adreno-EGL( 5259): Reconstruct Branch: 
,I/dalvikvm( 5259): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5259): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5259): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5259): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5259): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5259): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5259): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5259): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5259): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5259): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5259): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5259): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5259): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5259): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5259): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5259): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5259): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5259): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5259): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  248): id=16 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5259): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5259): Enabling debug mode 0
W/AwContents( 5259): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PowerManagerService(  746): [PWL] Off : 75s ago
D/CustomFrequencyManagerService(  746): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  746): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  746): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5300):  
W/GAV2    ( 5244): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5300):  
I/SELinux ( 5300):  
I/SELinux ( 5300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5300): >>>>> Normal User
E/dalvikvm( 5300): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5300): in addTimaSignatureService
D/TimaKeyStoreProvider( 5300): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5300): Added TimaKesytore provider
D/PackageIntentReceiver( 5300): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5300): Not GearManger package! 
I/SELinux ( 5319): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5319):  
I/ActivityManager(  746): Killing 3968:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5319): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5319):  
I/SELinux ( 5319):  
I/SELinux ( 5319): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5319): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5319): >>>>> Normal User
E/dalvikvm( 5319): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5319): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5319): in addTimaSignatureService
D/TimaKeyStoreProvider( 5319): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5319): Added TimaKesytore provider
D/JsMessageQueue( 5259): Set native->JS mode to OnlineEventsBridgeMode
D/MagazineService Version( 5319): Magazine-Channel: 13
D/MagazineService Version( 5319): Magazine-Provider: 13
D/MagazineService Version( 5319): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5319): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5319): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5319, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5319): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5335):  
D/MagazineService::MagazineService( 5319): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  746): Killing 1337:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/dalvikvm( 5259): Trying to load lib /data/app-lib/com.test.thalitest-3/libjxcore.so 0x42d6be20
I/SELinux ( 5335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5335):  
I/SELinux ( 5335):  
I/SELinux ( 5335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5244): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
E/dalvikvm( 5335): >>>>> Normal User
E/dalvikvm( 5335): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
D/dalvikvm( 5259): Added shared lib /data/app-lib/com.test.thalitest-3/libjxcore.so 0x42d6be20
D/jxcore_app_log( 5259): JniHelper::setJavaVM(0x41fa34f8), pthread_self() = 2025499736
D/JX-Cordova( 5259): jxcore cordova android initializing
E/SELinux ( 5335): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  746): Killing 4367:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/dalvikvm( 5259): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 5259): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5259): VFY: replacing opcode 0x6e at 0x0045
D/TimaKeyStoreProvider( 5335): in addTimaSignatureService
D/TimaKeyStoreProvider( 5335): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5335): Added TimaKesytore provider
I/SELinux ( 5350): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5350):  
I/ActivityManager(  746): Killing 4383:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
I/SELinux ( 5350): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5350):  
I/SELinux ( 5350):  
I/SELinux ( 5350): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5350): >>>>> Normal User
E/dalvikvm( 5350): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 5350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5350): in addTimaSignatureService
D/TimaKeyStoreProvider( 5350): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5350): Added TimaKesytore provider
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5350, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 5350): Package not found : com.sec.android.app.kidshome
D/dalvikvm( 5259): GC_CONCURRENT freed 4915K, 33% free 12771K/19000K, paused 3ms+2ms, total 33ms
D/dalvikvm( 5259): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/SELinux ( 5362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5362):  
I/ActivityManager(  746): Killing 4395:com.sec.esdk.elm/u0a94 (adj 15): empty #43
I/SELinux ( 5362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5362):  
I/SELinux ( 5362):  
I/SELinux ( 5362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5362): >>>>> Normal User
E/dalvikvm( 5362): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 5362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5362): in addTimaSignatureService
D/TimaKeyStoreProvider( 5362): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5362): Added TimaKesytore provider
I/ActivityManager(  746): Killing 3563:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
D/Finsky  ( 3665): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ChimeraCfgMgr( 1752): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1752): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraModuleLdr( 1752): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1752): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1752): Module APK com.google.android.play.games already loaded
D/CustomFrequencyManagerService(  746): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  tag : ACTIVITY_RESUME_BOOSTER@9
D/ChimeraCfgMgr( 1752): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1752): Submit a task: h
D/ChimeraCfgMgr( 1752): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1752): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1752): Processing package: com.test.thalitest
I/PeopleContactsSync( 1752): CP2 sync disabled
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
I/dalvikvm( 1752): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1752): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1752): VFY: replacing opcode 0x6e at 0x000e
D/a       ( 1752): Look up (com.test.thalitest:18) returned no result
D/h       ( 1752): Starting Hash for package com.test.thalitest:0.0.1
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
W/BaseAppContext( 1752): Using Auth Proxy for data requests.
D/dalvikvm( 5259): GC_FOR_ALLOC freed 4733K, 28% free 15757K/21824K, paused 34ms, total 34ms
,D/dalvikvm( 1752): GC_CONCURRENT freed 1726K, 40% free 11575K/19000K, paused 5ms+17ms, total 130ms
,W/SQLiteConnectionPool( 1752): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/GamesDatabaseHelper( 1752): Upgrading from version 720 to 1701
,D/dalvikvm( 5259): GC_FOR_ALLOC freed 5135K, 32% free 16787K/24552K, paused 35ms, total 41ms
,I/dalvikvm-heap( 5259): Grow heap (frag case) to 22.071MB for 2511452-byte allocation
,D/dalvikvm( 5259): GC_FOR_ALLOC freed 3810K, 36% free 17478K/27008K, paused 31ms, total 32ms
,E/SMD     (  242): DCD ON
,D/dalvikvm( 5259): GC_FOR_ALLOC freed 1245K, 36% free 17381K/27008K, paused 28ms, total 29ms
,W/jxcore-log( 5259): Initializing JXcore engine
,W/jxcore-log( 5259): JXcore engine is ready
,W/jxcore-log( 5259): Starting JXcore engine
,W/jxcore-log( 5259): Platform android
W/jxcore-log( 5259): 
,W/jxcore-log( 5259): Process ARCH arm
W/jxcore-log( 5259): 
,D/h       ( 1752): Package com.test.thalitest's hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/a       ( 1752): Look up (com.test.thalitest:18) returned no result
,D/h       ( 1752): Saved the app info in cache for package:com.test.thalitest.
,I/jxcore-log( 5259): JXcore Cordova bridge is ready!
I/jxcore-log( 5259): 
,W/jxcore-log( 5259): JXcore engine is started
,I/chromium( 5259): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5259): Toggling radios to true
I/jxcore-log( 5259): 
,D/BluetoothAdapter( 5259): enable(): BT is already enabled..!
,I/WifiManager( 5259): packageName : com.test.thalitest
,I/WifiManager( 5259): setWifiEnabled : true
,I/WifiService(  746): setWifiEnabled: true pid=5259, uid=10179
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5259, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  746): Failed getting userId using ActivityManagerNative
W/WifiService(  746): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5259, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  746): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  746): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  746): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  746): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  746): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  746): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService(  746): disconnect: pid=5259, uid=10179
,I/jxcore-log( 5259): Radios toggled
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1947): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1947): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering(  746): interfaceLinkStateChanged wlan0, false
D/Tethering(  746): interfaceStatusChanged wlan0, false
D/Tethering(  746): InitialState.processMessage what=4
,E/Tethering(  746): No numeric data
I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1947): Cmd 35605 not handled
E/wpa_supplicant( 1947): Cmd 35605 not handled
,I/wpa_supplicant( 1947): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/Tethering(  746): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  746): interfaceLinkStateChanged wlan0, false
,D/Tethering(  746): interfaceStatusChanged wlan0, false
V/NetworkStats(  746): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1947): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1947): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1947): First Scan Start
I/wpa_supplicant( 1947): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  746): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  746): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering(  746): interfaceLinkStateChanged wlan0, false
,D/Tethering(  746): interfaceStatusChanged wlan0, false
D/WifiP2pService(  746): InactiveState{ what=143375 }
D/WifiP2pService(  746): P2pEnabledState{ what=143375 }
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): performPollLocked() took 65ms
,I/wpa_supplicant( 1947): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1947): Skip scan - already scanning
D/NtpTrustedTime(  746): currentTimeMillis() cache hit
D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,I/WifiTrafficPoller(  746): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiP2pService(  746): InactiveState{ what=143375 }
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/WifiP2pService(  746): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  746): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  746): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  746): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  746): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  746): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  746): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/ConnectivityService(  746): Attempting to switch to mobile
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/ConnectivityService(  746): Attempting to switch to BLUETOOTH_TETHER
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  239): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 5393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5393):  
D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,D/CommandListener(  239): Clearing all IP addresses on wlan0
E/WifiStateMachine(  746): Error! unhandled message{ when=-57ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  746): Error! unhandled message{ when=-55ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService(  746): route cmd failed: 
W/NetworkManagementService(  746): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  746): '
W/NetworkManagementService(  746): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  746): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  746): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  746): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  746): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  746): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  746): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  746): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  746): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  746): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  746): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  746): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/WifiTrafficPoller(  746): evaluateTrafficStatsPolling
I/SELinux ( 5393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5393):  
I/SELinux ( 5393):  
I/SELinux ( 5393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5393): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5393): >>>>> Normal User
E/dalvikvm( 5393): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
E/SELinux ( 5393): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController(  239): /system/bin/ip -4 route del default table 2 2>&1
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  746): Error! unhandled message{ when=-1ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 5393): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5393): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5393): Added TimaKesytore provider
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  746): android_net_utils_resetConnections in env=0x78691b08 clazz=0x67f00001 iface=wlan0 mask=0x3
D/ConnectivityService(  746): resetConnections(wlan0, 3)
,D/ConnectivityService(  746): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): updateIfacesLocked()
V/NetworkStats(  746): performPollLocked(flags=0x1)
V/NetworkStats(  746): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): performPollLocked() took 18ms
D/NtpTrustedTime(  746): currentTimeMillis() cache hit
D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,I/System.out( 5393): Inside WakeupProvider
,I/System.out( 5393): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5393): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5393): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5393): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5393): initQueue()
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  746): Killing 4423:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/AmoledAdjustTimer(  746): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/ApplicationPolicy(  746): updateDataUsageMap
D/Tethering(  746): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  746): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  746): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  746): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  746): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  746): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  746): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/PCWCLIENTTRACE_PushUtil( 5138): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5138): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5138): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5138): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5138): noConnectivity : true
,I/NetworkMonitor( 3882): type=WIFI subType= reason=null isConnected=false
,I/SELinux ( 5423): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5423):  
,I/SELinux ( 5423): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5423):  
I/SELinux ( 5423):  
,I/SELinux ( 5423): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5423): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5423): >>>>> Normal User
E/dalvikvm( 5423): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
E/SELinux ( 5423): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5423): in addTimaSignatureService
D/TimaKeyStoreProvider( 5423): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5423): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5423, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  746): Killing 4438:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SELinux ( 5441): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5441):  
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 50% free 9506K/19000K, paused 3ms+2ms, total 25ms
,V/AlarmManager(  746): waitForAlarm result :4
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 1ms+3ms, total 18ms
I/SELinux ( 5441): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5441):  
I/SELinux ( 5441):  
,I/SELinux ( 5441): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5441): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5441): >>>>> Normal User
,E/dalvikvm( 5441): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5441): [DEBUG] seapp_context_lookup: seinfoCategory = release
V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 5441): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5441): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5441): Added TimaKesytore provider
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5441, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 1947): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 1947): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1947): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1947): Trying to associate with  'G700'
I/wpa_supplicant( 1947): Re-associate with C0.AA.48
,I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged wlan0, false
,D/Tethering(  746): interfaceStatusChanged wlan0, false
,I/GAV2    ( 5244): Thread[GAThread,5,main]: No campaign data found.
,E/wpa_supplicant( 1947): Cmd 35605 not handled
I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1947): Associated with C0.AA.48
I/wpa_supplicant( 1947): freq(2462) increment count 2
,I/wpa_supplicant( 1947): meet head of list.
E/wpa_supplicant( 1947): Cmd 35847 not handled
E/wpa_supplicant( 1947): Cmd 35848 not handled
E/wpa_supplicant( 1947): Cmd 35605 not handled
,I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  746): interfaceLinkStateChanged wlan0, false
,D/Tethering(  746): interfaceStatusChanged wlan0, false
,D/Tethering(  746): interfaceLinkStateChanged wlan0, false
,D/Tethering(  746): interfaceStatusChanged wlan0, false
,D/Tethering(  746): interfaceLinkStateChanged wlan0, false
,D/Tethering(  746): interfaceStatusChanged wlan0, false
,D/Tethering(  746): interfaceLinkStateChanged wlan0, true
,D/Tethering(  746): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1947): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1947): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
E/Tethering(  746): No numeric data
,I/wpa_supplicant( 1947): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  746): interfaceLinkStateChanged wlan0, true
,D/Tethering(  746): interfaceStatusChanged wlan0, true
,D/Tethering(  746): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
I/ConnectivityService(  746): defaultVal : 1, tetherEnabledInSettings : true
,V/NetworkStats(  746): performPollLocked(flags=0x1)
D/WifiNative(  746): callSECApiVoid - ID [50]
D/Tethering(  746): interfaceLinkStateChanged wlan0, true
,D/Tethering(  746): interfaceStatusChanged wlan0, true
,I/ActivityManager(  746): Killing 4463:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
D/Tethering(  746): interfaceLinkStateChanged wlan0, true
D/Tethering(  746): interfaceStatusChanged wlan0, true
D/Tethering(  746): interfaceLinkStateChanged wlan0, true
D/Tethering(  746): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): performPollLocked() took 49ms
D/WifiP2pService(  746): InactiveState{ what=143375 }
D/WifiP2pService(  746): P2pEnabledState{ what=143375 }
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,I/SELinux ( 5458): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5458):  
,I/SELinux ( 5458): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5458):  
I/SELinux ( 5458):  
,I/SELinux ( 5458): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5458): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5458): >>>>> Normal User
,E/dalvikvm( 5458): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5458): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/SMD     (  242): DCD ON
,D/TimaKeyStoreProvider( 5458): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5458): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5458): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5458, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/FactoryTest( 4726): Not factory mode
,D/FactoryTest( 4726): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4726): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4726): still no open session command from host, so toast
W/ContextImpl( 4726): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4726): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,D/dalvikvm(  746): GC_EXPLICIT freed 2527K, 58% free 23519K/55396K, paused 7ms+15ms, total 164ms
,I/dhcpcd  ( 5470): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5470): bssid match
,V/ApplicationPolicy(  746): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/KLMS-2.3.201 : ( 5458): KLMSValidator() : checkQATesting()
,D/CustomFrequencyManagerService(  746): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  746): mDVFSHelper.acquire()
,D/LockPatternUtils( 1068): isPcwEnable = null
,D/LockPatternUtils( 1068): isPcwEnable = null
,E/MTPRx   ( 4726): started activity for popup
,I/SQLiteSecureOpenHelper( 2095): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2095): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4726): PREF_DONT_ASK_AGAIN : false
,I/KLMS-2.3.201 : ( 5458): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449007408413
,I/KLMS-2.3.201 : ( 5458): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SettingsReceiverActivity( 4726): dev.kiessupport is : TRUE
I/ActivityManager(  746): Killing 4479:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5482): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5482):  
,I/SELinux ( 5482): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5482):  
I/SELinux ( 5482):  
I/SELinux ( 5482): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5482): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5482): >>>>> Normal User
E/dalvikvm( 5482): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5482): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5482): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5482): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5482): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5482, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,D/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SurfaceFlinger(  248): id=17 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4726): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4726): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4726): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4726): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4726): Remote Branch: 
I/Adreno-EGL( 4726): Local Patches: 
I/Adreno-EGL( 4726): Reconstruct Branch: 
,I/HWUI    ( 4726): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4726): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/SA      ( 4016): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4016): [BDLM] already registered in spp
,I/SA      ( 4016): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4016): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4016): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 4016): [OR] == isSIMCardReady false ==
,I/SA      ( 4016): [SCU] == networkStateCheck == false
,I/SA      ( 4016): [OR] onReceive END
I/ActivityManager(  746): Killing 4597:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/CustomFrequencyManagerService(  746): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  746): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  746): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SELinux ( 5497): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5497):  
D/SSRMv2:SIOP(  746): SIOP:: AP = 320, Delta = 10
,I/SELinux ( 5497): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5497):  
I/SELinux ( 5497):  
,I/SELinux ( 5497): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5497): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5497): >>>>> Normal User
,E/dalvikvm( 5497): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5497): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5497): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5497): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5497): Added TimaKesytore provider
,I/sCloudBackupApp( 5497): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5497): Other Intent
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/ActivityManager(  746): Killing 4608:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5510): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5510):  
,I/SELinux ( 5510): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5510):  
I/SELinux ( 5510):  
,I/SELinux ( 5510): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5510): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5510): >>>>> Normal User
,E/dalvikvm( 5510): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5510): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5510): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5510): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5510): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5510, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  746): Killing 4677:com.google.android.talk/u0a105 (adj 15): empty #43
,D/Headlines( 4076): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4076): getCountryCode(): countryCode = PL
D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4076): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4076): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4076): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4076): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4076): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4076): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5523):  
,I/SELinux ( 5523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5523):  
I/SELinux ( 5523):  
,I/SELinux ( 5523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5523): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5523): >>>>> Normal User
,E/dalvikvm( 5523): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5523): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5523): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5523): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5523): Added TimaKesytore provider
,W/GAV2    ( 5523): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5523): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5523): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5523): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/Vold    (  229): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5523): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/WebViewChromium( 5523): Binding Chromium to the main looper Looper (main, tid 1) {42a46f50}
,I/chromium( 5523): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5523): Initializing chromium process, renderers=0
,W/chromium( 5523): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5523): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5523): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5523): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5523): Remote Branch: 
I/Adreno-EGL( 5523): Local Patches: 
I/Adreno-EGL( 5523): Reconstruct Branch: 
,I/NSApplication( 5523): Starting up...
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5523, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  746): Killing 3006:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3350): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3350): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3350): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42d791f0
,I/SELinux ( 5557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5557):  
,I/SELinux ( 5557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5557):  
I/SELinux ( 5557):  
,I/SELinux ( 5557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5557): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5557): >>>>> Normal User
,E/dalvikvm( 5557): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5557): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5557): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5557): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5557): Added TimaKesytore provider
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/CustomFrequencyManagerService(  746): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 746  tag : ACTIVITY_RESUME_BOOSTER@9
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,I/SELinux ( 5576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5576):  
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
I/ActivityManager(  746): Killing 4771:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5576):  
I/SELinux ( 5576):  
,I/SELinux ( 5576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5576): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5576): >>>>> Normal User
,E/dalvikvm( 5576): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5576): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5582): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5582):  
,W/ActivityManager(  746): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 5576): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5576): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 5582): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5582):  
I/SELinux ( 5582):  
,I/SELinux ( 5582): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5582): >>>>> Normal User
,E/dalvikvm( 5582): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,D/ActivityThread( 5576): Added TimaKesytore provider
,E/SELinux ( 5582): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/ActivityManager(  746): Killing 4792:com.wssyncmldm/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5582): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5582): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5582): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5582, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5576): onCreate
,I/ActivityManager(  746): Killing 4638:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
D/BadgeProvider( 5576): DatabaseHelper
,D/BadgeProvider( 5576): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5576, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,I/iu.Environment( 1752): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/BadgeProvider( 5576): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5576): sendNotify, [notify] : null
D/BadgeProvider( 5576): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5576): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5576): update, [UpdateCount] : 1
,D/Launcher.Model( 1260): reloadBadges entered.
,I/jxcore-log( 5259): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5259): 
,I/iu.UploadsManager( 1752): num queued entries: 0
,I/jxcore-log( 5259): my name is : samsung-SM-G800H_PT2917
I/jxcore-log( 5259): 
,I/iu.UploadsManager( 1752): num updated entries: 0
,D/Headlines( 4076): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4076): Breath 1137 latestRequest time : 1449007409181 current time : 1449007410318
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,I/iu.SyncManager( 1752): NEXT; no task
,I/jxcore-log( 5259): attempting to connect to test coordinator
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): check test folder
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): found test : ./testFindPeers.js
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): found test : ./testReConnect.js
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): found test : ./testSendData.js
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): Test app app.js loaded
I/jxcore-log( 5259): 
D/WifiP2pService(  746): InactiveState{ what=143375 }
D/WifiP2pService(  746): P2pEnabledState{ what=143375 }
,I/Choreographer( 5259): Skipped 243 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/WifiStateMachine(  746): VerifyingLinkState enter
,I/chromium( 5259): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  746): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  746): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  746): evaluateTrafficStatsPolling
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  746): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  746): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  746): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  746): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  746): mBoosterFLAG : 2
,I/WifiTrafficPoller(  746): current booster mode : BTCoexMode
D/ConnectivityService(  746): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  746): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  746): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/ConnectivityService(  746): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such file or directory
D/Toast   ( 1311):  checkMirrorLinkEnabled returns : false
D/Toast   ( 1311): showing allowed
,V/RouteController(  239): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1311): MountReceiver.onReceive - Keep current state
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,I/SurfaceFlinger(  248): id=18 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/PowerManagerService(  746): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=746
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,V/NetworkStats(  746): updateIfacesLocked()
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
V/NetworkStats(  746): performPollLocked() took 18ms
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/NtpTrustedTime(  746): currentTimeMillis() cache hit
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,E/SMD     (  242): DCD ON
,D/Tethering(  746): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  746): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  746): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/accuweather( 1449): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  746): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  746): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  746): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3882): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5138): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5138): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5138): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5138): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/VacuumService( 1307): Vacuum at: now=1449007411469 tag=VacuumService
,I/KLMS-2.3.201 : ( 5458): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,V/GLSActivity( 1307): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1307): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1307): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/KLMS-2.3.201 : ( 5458): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449007411583
,I/KLMS-2.3.201 : ( 5458): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/GoogleURLConnFactory( 1307): Using platform SSLCertificateSocketFactory
,D/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 2547): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2547): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2547): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2547): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5482): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 2314): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5662): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5662):  
,I/SELinux ( 5662): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5662):  
I/SELinux ( 5662):  
,I/SELinux ( 5662): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5662): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5662): >>>>> Normal User
,E/dalvikvm( 5662): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5662): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5674): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5674):  
,D/TimaKeyStoreProvider( 5662): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5662): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5662): Added TimaKesytore provider
,I/SA      ( 4016): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4016): [BDLM] already registered in spp
I/SA      ( 4016): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4016): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 4016): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4016): [OR] == isSIMCardReady false ==
,I/SA      ( 4016): [SCU] == networkStateCheck == true
I/SA      ( 4016): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4016): isChinaCountryCode : false
,I/SA      ( 4016): [OR] == networkStateCheck true ==
,I/SA      ( 4016): [OR] GetMyCountryZoneTask
I/SA      ( 4016): [OR] onReceive END
I/SELinux ( 5674): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5674):  
I/SELinux ( 5674):  
,I/SELinux ( 5674): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5674): >>>>> Normal User
,E/dalvikvm( 5674): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5674): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 4016): [SRS] prepareGetMyCountryZone
,I/SA      ( 4016): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4016): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5497): Other Intent
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 5674): in addTimaSignatureService
,D/com.samsung.app( 1449): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 5674): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5674): Added TimaKesytore provider
,I/SA      ( 4016): [TPMU] GetMccFromDB : null
I/SA      ( 4016): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4016): [TPM] isNoProxy(default) : true
,I/SA      ( 4016): [RC New] Execute method=[GET] start
,D/Headlines( 4076): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4076): getCountryCode(): countryCode = PL
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4076): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4076): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4076): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4076): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4076): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4076): requestUpdateNewsWelcomeCard !!! no welcome card
,D/QuickConnect[1.1][2] ( 3350): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3350): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3350): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42d791f0
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,D/RCPManagerService(  746): exchangeData() failure , invalid userId
,V/KVNProvider( 5674): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5674): getFindoCursor query string : 
,V/KVNProvider( 5674): getTagSearchCursor() tagSearchCursor count : 0
,D/WaitQueueForNetworkActivate( 4176): notifyNetworkActivated
,D/hcjo    ( 4176): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4176): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4176): exit::IDLE
,D/InitializeManagerStateMachine( 4176): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4176): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4176): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4176): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4176): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4176): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4176): entry::SUCCESS
,D/hcjo    ( 4176): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4176): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4176): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4176): exit::SUCCESS
,D/InitializeManagerStateMachine( 4176): entry::IDLE
,I/iu.Environment( 1752): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1752): num queued entries: 0
I/ActivityManager(  746): Killing 4210:com.android.calendar/u0a142 (adj 15): empty #43
,I/iu.UploadsManager( 1752): num updated entries: 0
,I/iu.SyncManager( 1752): NEXT; no task
,I/GLSUser ( 1307): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/ads_measurement) -> status: null)
,I/GLSUser ( 1307): [GLSUser] Extracting token using key: Auth
,W/GLSUser ( 1307): [GLSUser] Permission for com.google.android.gms to access oauth2:https://www.googleapis.com/auth/ads_measurement will be managed locally.
,D/UdcCache:FPQuery( 1752): Bootstrapping UDC settings cache for all accounts
,I/dalvikvm( 1752): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1752): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1752): VFY: replacing opcode 0x71 at 0x0046
,D/dalvikvm( 1752): DexOpt: --- BEGIN 'ads-456512119.jar' (bootstrap=0) ---
,D/dalvikvm( 5697): DexOpt: load 4ms, verify+opt 13ms, 197964 bytes
,D/dalvikvm( 1752): DexOpt: --- END 'ads-456512119.jar' (success) ---
,D/dalvikvm( 1752): DEX prep '/data/data/com.google.android.gms/cache/ads-456512119.jar': unzip in 0ms, rewrite 170ms
,D/dalvikvm( 1752): GC_CONCURRENT freed 1795K, 38% free 11828K/19000K, paused 4ms+4ms, total 33ms
,D/dalvikvm( 1752): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SA      ( 4016): [RC New] [v2liruge] api execute + 657
,I/SA      ( 4016): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4016): AsyncTask #2 calls detatch()
,I/SA      ( 4016): [TPMU] getNetworkMcc : 
,I/SA      ( 4016): [SCU] saveMccToPreferece Start
,I/SA      ( 4016): [SCU] RegionMCC : 260
,I/SA      ( 4016): [SSP] query invoked
,I/SA      ( 4016): [TPMU] GetMccFromDB : null
I/SA      ( 4016): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4016): [SCU] saveMccToPreferece End
,I/SA      ( 4016): [RC New] executeRequest [v2liruge] end. 685
I/SA      ( 4016): [RC New] Execute end
I/SA      ( 4016): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4016): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  746): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,W/ActivityThread( 1752): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/WifiStateMachine(  746): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm(  746): GC_EXPLICIT freed 2286K, 58% free 23483K/55396K, paused 6ms+12ms, total 134ms
,I/System.out( 1752): Thread-201(HTTPLog):isShipBuild true
,I/System.out( 1752): Thread-201(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SurfaceFlinger(  248): id=18 Removed Uoast (12/13)
,I/SurfaceFlinger(  248): id=18 Removed Uoast (-2/13)
,I/ActivityManager(  746): Killing 4624:com.android.providers.calendar/u0a44 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  746): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=746 (0x0)
D/PowerManagerService(  746): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=746, ws=WorkSource{1000}) (elapsedTime=3467)
,E/SMD     (  242): DCD ON
,I/GAV2    ( 5523): Thread[GAThread,5,main]: No campaign data found.
,I/HarmonyEASService(  746): Updating for all 1
,W/WifiP2pStateTracker(  746): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  746): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  746):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  746): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  746): updateSourceRoutes : no source routing conditions
,I/jxcore-log( 5259): BLE advertisement not supported: Build version is 19
I/jxcore-log( 5259): 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5138): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5138): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5138): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5138): ================================================
,I/CSTORAGE( 5138):  CSTORAGE_SKM_LIB v1.0.14
,I/CSTORAGE( 5138): ================================================
,D/dalvikvm( 5138): No JNI_OnLoad found in /system/lib/libterrier.so 0x42d73340, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5138): [GetString-S]
,I/terrier ( 5138): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 5138): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5138): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5138): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 5138): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5138): QSEECom_shutdown_app, app_id = 4
,E/terrier ( 5138): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5138): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5138): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5138): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5138): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5138): [ensureRegistration] - No Samsung account
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 288, currTemp = 290, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,V/AlarmManager(  746): waitForAlarm result :4
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP(  746): SIOP:: AP = 310, Delta = -10
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3665): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3665): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker(  746): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  746): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  746): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  746): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  746): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  746): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  746): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  746): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4176): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4176): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4176): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4176): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4176): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4176): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4176): entry::IDLE
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 4
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 290, currTemp = 294, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = -10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,V/AlarmManager(  746): waitForAlarm result :8
,D/Headlines( 4076): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4076): Breath 18759 latestRequest time : 1449007411835 current time : 1449007430594
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  746): [PWL] Off : 105s ago
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 294, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,E/SMD     (  242): DCD ON
D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 5
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  746): waitForAlarm result :8
,D/Headlines( 4076): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4076): Breath 48751 latestRequest time : 1449007411835 current time : 1449007460587
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService(  746): [PWL] Off : 140s ago
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 6
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,D/Headlines( 4076): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4076): Breath 78745 latestRequest time : 1449007411835 current time : 1449007490582
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  746): stay LED for fully charged
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 1307): disconnect managed GoogleApiClient
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  746): [PWL] Off : 180s ago
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 7
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  746): waitForAlarm result :8
,D/Headlines( 4076): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4076): Breath 108747 latestRequest time : 1449007411835 current time : 1449007520582
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 8
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,D/Headlines( 4076): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4076): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4076): Breath 138746 latestRequest time : 1449007411835 current time : 1449007550583
,D/Headlines( 4076): stop 
,D/Headlines( 4076): Breath.onDestroy : 
,I/ActivityManager(  746): Killing 4411:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  746): [PWL] Off : 225s ago
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  242): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 9
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5259): DBG, CoordinatorConnector connect called
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): Coordinator is now connected to the server!
I/jxcore-log( 5259): 
,I/chromium( 5259): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/TimaService(  746): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  746): TimaServiceHandler.handleMessage what =1
,D/TimaService(  746): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  746): initializing...
,I/TLC_TIMA_PKM_initialize(  746): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  746): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  746): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  746): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  746): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  746): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  746): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  746): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  746): App is not loaded in QSEE
,D/QSEECOMAPI: (  746): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  746): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  746): Trustlet response is completed
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,I/PowerManagerService(  746): [PWL] Off : 275s ago
,I/PowerManagerService(  746): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  746): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  746): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=746, ws=null) (elapsedTime=3275)
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  746): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  746): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  746): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  746): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  746): !@Sync 10
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  746): waitForAlarm result :4
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,I/SELinux ( 5789): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5789):  
,V/AlarmManager(  746): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/dalvikvm(  249): GC_EXPLICIT freed 42K, 50% free 9506K/19000K, paused 13ms+41ms, total 335ms
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 35ms+32ms, total 189ms
,I/SELinux ( 5789): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5789):  
I/SELinux ( 5789):  
,I/SELinux ( 5789): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5789): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5789): >>>>> Normal User
,E/dalvikvm( 5789): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5789): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 18ms+39ms, total 197ms
,D/TimaKeyStoreProvider( 5789): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5789): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5789): Added TimaKesytore provider
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5789, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  746): Killing 4574:com.sec.phone/1001 (adj 15): empty #43
,I/EventLogService( 1752): Aggregate from 1449005806694 (log), 1449005806694 (data)
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  746): !@Sync 11
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  746): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  746): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  746): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  746): !@Sync 12
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  746): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  746): !@Sync 13
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): DBG, CoordinatorConnector command called
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"90:E7:C4:F6:69
,I/jxcore-log( 5259): Start now : testSendData.js
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): check server
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): serverPort is 41366
I/jxcore-log( 5259): 
,I/        ( 5259): Stoping All
,I/        ( 5259): Stopping services
,I/        ( 5259): Stop Bluetooth
,I/        ( 5259): Start-My BT: 38:94:96:B5:06:DC
,I/        ( 5259):  mInstanceString : {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}
,I/        ( 5259): All stuff available and enabled
,I/        ( 5259): Stoping All
I/        ( 5259): Stopping services
,I/        ( 5259): Stop Bluetooth
I/        ( 5259): Starting All
,I/        ( 5259): Stopping services
,I/        ( 5259): Starting services address: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@42dfc598
,I/        ( 5259): Stopping services
,I/        ( 5259): Starting services address: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}
,I/        ( 5259): Add local service :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, length : 82
,I/        ( 5259): peerDiscoveryTimer timeout value:5086
,D/WifiP2pService(  746): InactiveState{ what=139292 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  746): P2pEnabledState add service
,D/WifiP2pService(  746): add a new client
,I/        ( 5259): Stop Bluetooth
,I/        ( 5259): StartBluetooth listener
,I/        ( 5259): StartBluetooth listener
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_iface_process] : P2P_STOP_FIND
D/WifiP2pService(  746): InactiveState{ what=139268 }
,E/BluetoothServiceJni( 1951): SOCK FLAG = 0 ***********************
,D/WifiP2pService(  746): InactiveState{ what=139265 }
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
I/jxcore-log( 5259): StartBroadcasting started ok
I/jxcore-log( 5259): 
I/jxcore-log( 5259): do fake peer & start
I/jxcore-log( 5259): 
I/BTListenerThread( 5259): starting to listen
I/BTListenerThread( 5259): waiting to accept incoming Connection
I/jxcore-log( 5259): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:24.322Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 5259): 2015-12-01T22:08:24.334Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:24.346Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,D/WifiP2pService(  746): discovery change broadcast true
,I/        ( 5259): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 5259): Connecting to null, at 58:2A:F7:ED:96:BE
,I/jxcore-log( 5259): 2015-12-01T22:08:24.391Z SendDataTCPServer.js: TCP/IP server is bound to port: 41366
I/jxcore-log( 5259): 
,I/chromium( 5259): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 5259): We already were running, thus doing nothing
I/        ( 5259): Added local service
,I/BTConnectToThread( 5259): Starting to connect
,I/        ( 5259): Cleared service requests
,I/        ( 5259): Stopped peer discovery
,I/        ( 5259): Started peer discovery
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
I/        ( 5259): Discovery state changed to Started.
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 82.E8.5D p2p_dev_addr=82.E8.5D pri_dev_type=10-0050F204-5   '63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 1 peers.
,I/SS      ( 5259): Peer(1): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
D/WifiP2pManager( 5259): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 5259): Added service request
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 82.E8.5D p2p_dev_addr=82.E8.5D pri_dev_type=10-0050F204-5   '63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started service discovery
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/BluetoothRemoteDevices( 1951): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  746): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND B6.A4.6B p2p_dev_addr=B6.A4.6B pri_dev_type=10-0050F204-5   '1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/BluetoothBondStateMachine( 1951): Entering PendingCommandState State
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/IOP_DB_BT( 1951): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,I/CachedBluetoothDevice( 1311): updateProfiles
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btif ( 1951): services_to_search = 3fffffff
,E/bt-btif ( 1951): ****************search UUID = 1200***********
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/bt-btif ( 1951): services_to_search = 3ffffffe
,E/bt-btif ( 1951): ****************search UUID = 0100***********
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTConnectToThread( 5259): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4585","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : HUAWEI-ALE-L21_PT4585
,I/HS      ( 5259): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT4585
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 39765
,I/BtConnectorHelper( 5259): Request socket is using : 39765
,I/BtToRequestSocket( 5259): Now accepting connections
,E/bt-btif ( 1951): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 8 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/HidService( 1951): getHidService(): returning com.android.bluetooth.hid.HidService@42dbdd18
,D/HidService( 1951): Saved priority 58:2A:F7:ED:96:BE = -1
,I/BluetoothBondStateMachine( 1951): StableState(): Entering Off State
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.UUID
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  746): GC_CONCURRENT freed 3427K, 58% free 23510K/55396K, paused 68ms+15ms, total 574ms
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
D/GMFPReceiver( 5300): ::::::::Wearable0001::false
I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :39765
I/jxcore-log( 5259): 2015-12-01T22:08:30.105Z SendDataConnector.js: CLIENT connected to 39765, error: null
I/jxcore-log( 5259): 
I/jxcore-log( 5259): 2015-12-01T22:08:30.105Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 39765
,I/BtToRequestSocket( 5259): Set local streams
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
D/GMFPReceiver( 5300): ::::::::Wearable0002::false
I/jxcore-log( 5259): 2015-12-01T22:08:30.116Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5259): 
I/BtToRequestSocket( 5259): rin ended ---------------------------;
D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5300): jangil::setProperties()
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:08:31.486Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:31.650Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:31.884Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:31.942Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:31.972Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5259): 
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/jxcore-log( 5259): 2015-12-01T22:08:32.642Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:32.692Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5259): 
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 36.0A.E2 p2p_dev_addr=36.0A.E2 pri_dev_type=10-0050F204-5   's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:08:33.447Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,E/SMD     (  242): DCD ON
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
,I/        ( 5259): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  746): prevTemp = 280, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService(  746): [PWL] Off : 390s ago
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=139265 }
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EA.28.A3 p2p_dev_addr=EA.28.A3 pri_dev_type=10-0050F204-5   'e3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,I/jxcore-log( 5259): 2015-12-01T22:08:43.473Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,I/jxcore-log( 5259): 2015-12-01T22:08:43.497Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,I/jxcore-log( 5259): 2015-12-01T22:08:43.538Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:43.572Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:43.577Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 5259): Disconnect outgoing peer: HUAWEI-ALE-L21_PT4585
I/BtToSocketBase( 5259): Stop ReceivingThread
I/BtToSocketBase( 5259): Stop SendingThread
I/BtToSocketBase( 5259): Close local in
I/BtToSocketBase( 5259): Close LocalOutputStream
I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 9 peers.
,I/SS      ( 5259): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(6): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(7): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 5259): Peer(8): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(9): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
,D/WifiP2pManager( 5259): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 5259): Added service request
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started service discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/Watchdog(  746): !@Sync 14
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 82.E8.5D p2p_dev_addr=82.E8.5D pri_dev_type=10-0050F204-5   '63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/AmoledAdjustTimer(  746): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5259): 2015-12-01T22:08:48.577Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:48.579Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:08:53.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:53.596Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:53.598Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:53.599Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 5259): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
,I/        ( 5259): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,I/SELinux ( 5863): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5863):  
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-59242343,-50000000) -- cpu overload ? #####
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-54900363,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-60101874,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-51483957,-50000000) -- cpu overload ? #####
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-79715363,-50000000) -- cpu overload ? #####
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-91940988,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-89839947,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-81224999,-50000000) -- cpu overload ? #####
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-74936040,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-71263488,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-68270310,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-59654009,-50000000) -- cpu overload ? #####
,E/GKI_LINUX( 1951): ##### ERROR : timer_thread: tick delayed > 5 slots (-51849113,-50000000) -- cpu overload ? #####
,D/AmoledAdjustTimer(  746): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/SELinux ( 5863): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5863):  
I/SELinux ( 5863):  
,I/SELinux ( 5863): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
E/SELinux ( 5863): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5863): >>>>> Normal User
,E/dalvikvm( 5863): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 5863): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/TimaKeyStoreProvider( 5863): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5863): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5863): Added TimaKesytore provider
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/UserAnalysis.PlaceProvider( 5863): Create SecureDbHelper
,W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=5863, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,I/ActivityManager(  746): Killing 4541:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTConnectToThread( 5259): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4585","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 5259): HandshakeOk : HUAWEI-ALE-L21_PT4585
,I/HS      ( 5259): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT4585
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 32796
I/BtConnectorHelper( 5259): Request socket is using : 32796
,I/BtToRequestSocket( 5259): Now accepting connections
,E/SMD     (  242): DCD ON
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :32796
,I/jxcore-log( 5259): 2015-12-01T22:08:58.582Z SendDataConnector.js: CLIENT connected to 32796, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:08:58.583Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 32796
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:08:58.595Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): InactiveState{ what=139265 }
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND F4.43.C8 p2p_dev_addr=F4.43.C8 pri_dev_type=10-0050F204-5   '8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 10 peers.
,I/SS      ( 5259): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 5259): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 5259): Peer(7): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(8): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 5259): Peer(9): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
D/WifiP2pManager( 5259): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 5259): Added service request
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started service discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  746): mCoverManager.getCoverState() : true
D/BatteryService(  746): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  746): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:09:08.755Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:08.756Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:08.759Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:08.761Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:08.764Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:09:13.764Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:13.765Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog(  746): !@Sync 15
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
,I/        ( 5259): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 5259): 2015-12-01T22:09:18.771Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:18.772Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:18.773Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:18.775Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 5259): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,E/SMD     (  242): DCD ON
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTConnectToThread( 5259): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4585","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 5259): HandshakeOk : HUAWEI-ALE-L21_PT4585
I/HS      ( 5259): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT4585
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 52414
,I/BtConnectorHelper( 5259): Request socket is using : 52414
,I/BtToRequestSocket( 5259): Now accepting connections
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :52414
,I/jxcore-log( 5259): 2015-12-01T22:09:21.549Z SendDataConnector.js: CLIENT connected to 52414, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:21.551Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 52414
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:09:21.569Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND FA.E5.62 p2p_dev_addr=FA.E5.62 pri_dev_type=10-0050F204-5   '50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
D/WifiP2pService(  746): InactiveState{ what=139265 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative(  746): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5   ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 13 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 5259): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(5): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 5259): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 5259): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(10): Note4-1 92:b6:86:43:73:1c
I/SS      ( 5259): Peer(11): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 5259): Peer(12): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(13): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo,: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiP2pService(  746): InactiveState{ what=139301 }
D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
D/WifiP2pManager( 5259): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 5259): Added service request
D/WifiP2pService(  746): P2pEnabledState add service request
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5   '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started service discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/dalvikvm(  746): GC_CONCURRENT freed 3234K, 57% free 23693K/54616K, paused 39ms+19ms, total 417ms
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EA.28.A3 p2p_dev_addr=EA.28.A3 pri_dev_type=10-0050F204-5   'e3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  7,46):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:09:31.763Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:31.763Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:31.766Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:31.768Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:31.771Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EA.28.A3 p2p_dev_addr=EA.28.A3 pri_dev_type=10-0050F204-5   'e3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:09:36.770Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:36.772Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:09:41.778Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:41.779Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:41.780Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:41.782Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 5259): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/PowerManagerService(  746): [PWL] Off : 455s ago
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BTConnectToThread( 5259): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4585","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : HUAWEI-ALE-L21_PT4585
,I/HS      ( 5259): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT4585
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 38827
,I/BtConnectorHelper( 5259): Request socket is using : 38827
,I/BtToRequestSocket( 5259): Now accepting connections
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :38827
,I/jxcore-log( 5259): 2015-12-01T22:09:44.996Z SendDataConnector.js: CLIENT connected to 38827, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:44.997Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 38827
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:09:45.003Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,E/Watchdog(  746): !@Sync 16
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5   '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc65b4 rs_disc_pending=0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:09:55.077Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:55.078Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:55.081Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:55.084Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:09:55.086Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 5259): Disconnect outgoing peer: HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): Stop ReceivingThread
I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND FA.E5.62 p2p_dev_addr=FA.E5.62 pri_dev_type=10-0050F204-5   '50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5259): 2015-12-01T22:10:00.087Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:00.087Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
,I/        ( 5259): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:10:05.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:05.095Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:05.096Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:05.098Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 5259): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
D/WifiP2pService(  746): InactiveState{ what=139265 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/AmoledAdjustTimer(  746): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
D/WifiP2pManager( 5259): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 5259): Added service request
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started service discovery
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1951): aclStateChangeCallback: Device is NULL
,I/BTConnectToThread( 5259): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT4585","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : HUAWEI-ALE-L21_PT4585
,I/HS      ( 5259): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT4585
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT4585
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 44243
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BtConnectorHelper( 5259): Request socket is using : 44243
,I/BtToRequestSocket( 5259): Now accepting connections
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc65b4 rs_disc_pending=1
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :44243
,I/jxcore-log( 5259): 2015-12-01T22:10:11.019Z SendDataConnector.js: CLIENT connected to 44243, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:11.030Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 44243
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:10:11.048Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/BluetoothBondStateMachine( 1951): Entering PendingCommandState State
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,D/IOP_DB_BT( 1951): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btif ( 1951): services_to_search = 3fffffff
,E/bt-btif ( 1951): ****************search UUID = 1200***********
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,E/bt-btif ( 1951): services_to_search = 3ffffffe
,E/bt-btif ( 1951): ****************search UUID = 0100***********
,I/BTListenerThread( 5259): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6355
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/jxcore-log( 5259): 2015-12-01T22:10:12.047Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,E/bt-btif ( 1951): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb,
,E/bt-btif ( 1951): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/HidService( 1951): getHidService(): returning com.android.bluetooth.hid.HidService@42dbdd18
,D/HidService( 1951): Saved priority 08:EC:A9:50:76:27 = -1
,I/BluetoothBondStateMachine( 1951): StableState(): Entering Off State
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.UUID
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:10:12.814Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:12.822Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:12.869Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:12.879Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:12.882Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:12.893Z SendDataTCPServer.js: TCP/IP server has received 10216 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.044Z SendDataTCPServer.js: TCP/IP server has received 12240 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.083Z SendDataTCPServer.js: TCP/IP server has received 14264 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.125Z SendDataTCPServer.js: TCP/IP server has received 16288 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.130Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.193Z SendDataTCPServer.js: TCP/IP server has received 18408 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.203Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.222Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.246Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.282Z SendDataTCPServer.js: TCP/IP server has received 32576 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.362Z SendDataTCPServer.js: TCP/IP server has received 34600 bytes of data
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:10:13.398Z SendDataTCPServer.js: TCP/IP server has received 36624 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.416Z SendDataTCPServer.js: TCP/IP server has received 38648 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.428Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.472Z SendDataTCPServer.js: TCP/IP server has received 42696 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.512Z SendDataTCPServer.js: TCP/IP server has received 46744 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.547Z SendDataTCPServer.js: TCP/IP server has received 48768 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.557Z SendDataTCPServer.js: TCP/IP server has received 50792 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.568Z SendDataTCPServer.js: TCP/IP server has received 52816 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.602Z SendDataTCPServer.js: TCP/IP server has received 54840 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.628Z SendDataTCPServer.js: TCP/IP server has received 56864 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.639Z SendDataTCPServer.js: TCP/IP server has received 58888 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.647Z SendDataTCPServer.js: TCP/IP server has received 60912 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.692Z SendDataTCPServer.js: TCP/IP server has received 62936 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.732Z SendDataTCPServer.js: TCP/IP server has received 73056 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.771Z SendDataTCPServer.js: TCP/IP server has received 75080 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.804Z SendDataTCPServer.js: TCP/IP server has received 83176 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.814Z SendDataTCPServer.js: TCP/IP server has received 85200 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.848Z SendDataTCPServer.js: TCP/IP server has received 87224 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.854Z SendDataTCPServer.js: TCP/IP server has received 89248 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.866Z SendDataTCPServer.js: TCP/IP server has received 91272 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.878Z SendDataTCPServer.js: TCP/IP server has received 95320 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:13.913Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5259): 
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/Watchdog(  746): !@Sync 17
,E/SMD     (  242): DCD ON
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/jxcore-log( 5259): 2015-12-01T22:10:21.252Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.252Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.255Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.282Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.283Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.284Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
,I/BtToSocketBase( 5259): Stop ReceivingThread
I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 5259): Close LocalOutputStream
I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,I/jxcore-log( 5259): 2015-12-01T22:10:21.322Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): ---- round done--------
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): do fake peer & start
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.334Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.335Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:21.337Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 5259): Connecting to null, at E0:DB:10:1F:C9:5E
,I/jxcore-log( 5259): 2015-12-01T22:10:21.405Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,I/chromium( 5259): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 1951): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc65b4 rs_disc_pending=0
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/BluetoothBondStateMachine( 1951): Entering PendingCommandState State
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,D/IOP_DB_BT( 1951): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btif ( 1951): services_to_search = 3fffffff
,E/bt-btif ( 1951): ****************search UUID = 1200***********
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/jxcore-log( 5259): 2015-12-01T22:10:24.373Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc65b4 rs_disc_pending=1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,E/bt-btif ( 1951): services_to_search = 3ffffffe
,E/bt-btif ( 1951): ****************search UUID = 0100***********
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTConnectToThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : samsung-SM-N9005_PT2504
,I/HS      ( 5259): Hand Shake finished outgoing for : samsung-SM-N9005_PT2504
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 44640
,I/BtConnectorHelper( 5259): Request socket is using : 44640
,I/BtToRequestSocket( 5259): Now accepting connections
,E/SMD     (  242): DCD ON
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :44640
,I/jxcore-log( 5259): 2015-12-01T22:10:25.673Z SendDataConnector.js: CLIENT connected to 44640, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:25.675Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 44640
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:10:25.696Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,E/bt-btif ( 1951): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb,
,E/bt-btif ( 1951): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb,
,E/bt-btif ( 1951): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/HidService( 1951): getHidService(): returning com.android.bluetooth.hid.HidService@42dbdd18
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HidService( 1951): Saved priority E0:DB:10:1F:C9:5E = -1
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/BackupManagerService(  746): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/BluetoothBondStateMachine( 1951): StableState(): Entering Off State
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.UUID
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 58:2a:f7:ed:96:be
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:10:27.136Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.226Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.314Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.317Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.432Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.513Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.633Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.662Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:27.736Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 5259): 
,D/AmoledAdjustTimer(  746): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/dalvikvm(  746): GC_CONCURRENT freed 3366K, 57% free 23784K/54616K, paused 46ms+19ms, total 618ms
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,E/bt-btif ( 1951): bta_dm_pm_btm_status  hci_status=42
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:76:27]: 6, 10f, 608
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTListenerThread( 5259): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6355
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:10:36.174Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,I/jxcore-log( 5259): 2015-12-01T22:10:36.547Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:36.562Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:36.575Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:36.591Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:36.596Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:36.604Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:10:37.733Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:37.734Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:37.736Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:37.739Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:37.741Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 5259): Disconnect outgoing peer: samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): Stop ReceivingThread
I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,D/AmoledAdjustTimer(  746): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND F4.43.C8 p2p_dev_addr=F4.43.C8 pri_dev_type=10-0050F204-5   '8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
I/        ( 5259): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:10:42.741Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:42.742Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/SMD     (  242): DCD ON
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/Watchdog(  746): !@Sync 18
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): InactiveState{ what=139265 }
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): Stop ReceivingThread
I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt in
I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt socket
,I/BtToSocketBase( 5259): Close bt socket
,I/jxcore-log( 5259): 2015-12-01T22:10:46.633Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-00,50F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/Tethering(  746): interfaceLinkStateChanged p2p0, false
D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
,D/WifiP2pManager( 5259): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 5259): Added service request
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/jxcore-log( 5259): 2015-12-01T22:10:47.748Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:47.749Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:47.752Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:47.753Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 5259): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/AmoledAdjustTimer(  746): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started service discovery
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,I/BTConnectToThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : samsung-SM-N9005_PT2504
,I/HS      ( 5259): Hand Shake finished outgoing for : samsung-SM-N9005_PT2504
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 48994
,I/BtConnectorHelper( 5259): Request socket is using : 48994
,I/BtToRequestSocket( 5259): Now accepting connections
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :48994
,I/jxcore-log( 5259): 2015-12-01T22:10:50.713Z SendDataConnector.js: CLIENT connected to 48994, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:10:50.714Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 48994
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:10:50.731Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  746): [PWL] Off : 525s ago
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,E/bt-btif ( 1951): bta_dm_pm_btm_status  hci_status=42
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 271
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 6:1544
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/SMD     (  242): DCD ON
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5259): 2015-12-01T22:11:00.955Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:00.955Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:00.958Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:00.960Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:00.963Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: samsung-SM-N9005_PT2504
I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/wpa_supplicant( 1947): P2P: Ignore unexpected GAS Initial Response from 02:f4:6f:30:e0:6d
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND F4.43.C8 p2p_dev_addr=F4.43.C8 pri_dev_type=10-0050F204-5   '8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:11:05.963Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:05.966Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
I/        ( 5259): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,I/        ( 5259): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5259): 2015-12-01T22:11:10.970Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:10.971Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:10.973Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:10.974Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 5259): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,I/BTConnectToThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : samsung-SM-N9005_PT2504
,I/HS      ( 5259): Hand Shake finished outgoing for : samsung-SM-N9005_PT2504
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 51122
,I/BtConnectorHelper( 5259): Request socket is using : 51122
,I/BtToRequestSocket( 5259): Now accepting connections
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :51122
,I/jxcore-log( 5259): 2015-12-01T22:11:13.078Z SendDataConnector.js: CLIENT connected to 51122, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:13.080Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 51122
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:11:13.098Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,E/SMD     (  242): DCD ON
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): InactiveState{ what=139265 }
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pManager( 5259): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 5259): Added service request
D/WifiP2pService(  746): P2pEnabledState add service request
,E/Watchdog(  746): !@Sync 19
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started service discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 82.E8.5D p2p_dev_addr=82.E8.5D pri_dev_type=10-0050F204-5   '63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1951): Disconnected process message: 10
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 5259): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/SMD     (  242): DCD ON
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:11:23.291Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:23.292Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:23.295Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:23.296Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:23.299Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): InactiveState{ what=139265 }
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND F4.43.C8 p2p_dev_addr=F4.43.C8 pri_dev_type=10-0050F204-5   '8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pManager( 5259): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 5259): Added service request
D/WifiP2pService(  746): P2pEnabledState add service request
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started service discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): 2015-12-01T22:11:28.299Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:28.300Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD ON
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/dalvikvm(  746): GC_CONCURRENT freed 3443K, 57% free 23935K/54616K, paused 37ms+19ms, total 480ms
,D/dalvikvm(  746): WAIT_FOR_CONCURRENT_GC blocked 446ms
D/dalvikvm(  746): WAIT_FOR_CONCURRENT_GC blocked 444ms
,D/dalvikvm(  746): WAIT_FOR_CONCURRENT_GC blocked 445ms
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, ,deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EA.28.A3 p2p_dev_addr=EA.28.A3 pri_dev_type=10-0050F204-5   'e3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 5259): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:11:33.304Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:33.305Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:33.307Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:33.309Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 5259): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,E/SMD     (  242): DCD ON
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): InactiveState{ what=139265 }
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/        ( 5259): Started peer discovery
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  746): InactiveState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pManager( 5259): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 5259): Added service request
D/WifiP2pService(  746): P2pEnabledState add service request
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative(  746): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started service discovery
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/SMD     (  242): DCD ON
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTListenerThread( 5259): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6355
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): stay LED for fully charged
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  746): mCoverManager.getCoverState() : true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/jxcore-log( 5259): 2015-12-01T22:11:38.464Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/jxcore-log( 5259): 2015-12-01T22:11:38.808Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:38.815Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:38.819Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:38.823Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:38.826Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,I/BTConnectToThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : samsung-SM-N9005_PT2504
I/HS      ( 5259): Hand Shake finished outgoing for : samsung-SM-N9005_PT2504
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 57061
,I/BtConnectorHelper( 5259): Request socket is using : 57061
,I/BtToRequestSocket( 5259): Now accepting connections
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :57061
,I/jxcore-log( 5259): 2015-12-01T22:11:39.206Z SendDataConnector.js: CLIENT connected to 57061, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:39.208Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 57061
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:11:39.239Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,D/TimaService(  746): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  746): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  746): TimaServiceHandler.handleMessage what =1
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6770 rs_disc_pending=0
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/TLC_TIMA_PKM_measure_kernel(  746): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  746): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  746): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  746): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/Watchdog(  746): !@Sync 20
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,E/SMD     (  242): DCD ON
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 82.E8.5D p2p_dev_addr=82.E8.5D pri_dev_type=10-0050F204-5   '63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:11:49.398Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:11:49.461Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:49.462Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:49.465Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:49.469Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:11:49.487Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/BtToSocketBase( 5259): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6770 rs_disc_pending=1
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5   ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1951): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6770 rs_disc_pending=1
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/jxcore-log( 5259): 2015-12-01T22:11:54.493Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/BluetoothBondStateMachine( 1951): Entering PendingCommandState State
,I/jxcore-log( 5259): 2015-12-01T22:11:54.500Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/IOP_DB_BT( 1951): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btif ( 1951): services_to_search = 3fffffff
,E/bt-btif ( 1951): ****************search UUID = 1200***********
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTListenerThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,E/bt-btif ( 1951): services_to_search = 3ffffffe
,E/bt-btif ( 1951): ****************search UUID = 0100***********
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT2405
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-N910C_PT2405
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:11:55.043Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,E/bt-btif ( 1951): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1951): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/HidService( 1951): getHidService(): returning com.android.bluetooth.hid.HidService@42dbdd18
,D/HidService( 1951): Saved priority E0:DB:10:14:E2:C0 = -1
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/BluetoothBondStateMachine( 1951): StableState(): Entering Off State
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.UUID
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,E/SMD     (  242): DCD ON
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,I/jxcore-log( 5259): 2015-12-01T22:11:55.656Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.677Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.682Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.692Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 5259): 
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/jxcore-log( 5259): 2015-12-01T22:11:55.766Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.783Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.829Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.862Z SendDataTCPServer.js: TCP/IP server has received 34408 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.967Z SendDataTCPServer.js: TCP/IP server has received 36432 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.977Z SendDataTCPServer.js: TCP/IP server has received 38456 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.981Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:55.992Z SendDataTCPServer.js: TCP/IP server has received 44528 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.105Z SendDataTCPServer.js: TCP/IP server has received 46552 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.142Z SendDataTCPServer.js: TCP/IP server has received 54648 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.207Z SendDataTCPServer.js: TCP/IP server has received 56672 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.243Z SendDataTCPServer.js: TCP/IP server has received 58696 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.314Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.451Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.485Z SendDataTCPServer.js: TCP/IP server has received 68816 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.521Z SendDataTCPServer.js: TCP/IP server has received 70840 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.533Z SendDataTCPServer.js: TCP/IP server has received 72864 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.562Z SendDataTCPServer.js: TCP/IP server has received 78936 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.701Z SendDataTCPServer.js: TCP/IP server has received 80960 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.709Z SendDataTCPServer.js: TCP/IP server has received 82984 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.742Z SendDataTCPServer.js: TCP/IP server has received 85008 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.766Z SendDataTCPServer.js: TCP/IP server has received 87032 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.776Z SendDataTCPServer.js: TCP/IP server has received 89056 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.984Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:56.998Z SendDataTCPServer.js: TCP/IP server has received 95128 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:57.032Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND F4.43.C8 p2p_dev_addr=F4.43.C8 pri_dev_type=10-0050F204-5   '8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 5259): 2015-12-01T22:11:59.513Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:59.514Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:59.516Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:11:59.518Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 5259): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[123]}
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  746): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
E/wpa_supplicant( 1947): Cmd 35609 not handled
D/Tethering(  746): interfaceLinkStateChanged p2p0, false
D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/wpa_supplicant( 1947): P2P: Ignore unexpected GAS Initial Response from 02:f4:6f:30:e0:6d
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 0)
,E/bt-btif ( 1951): BTA_JvRfcommConnect
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTConnectToThread( 5259): Starting to Handshake
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 5259): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTConnectToThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 5259): HandshakeOk : samsung-SM-N9005_PT2504
,I/HS      ( 5259): Hand Shake finished outgoing for : samsung-SM-N9005_PT2504
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : false, samsung-SM-N9005_PT2504
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): mHTTPPort  set to : 32994
,I/BtConnectorHelper( 5259): Request socket is using : 32994
,I/BtToRequestSocket( 5259): Now accepting connections
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BtConnectorHelper( 5259): Calling ConnectionStatusUpdate with port :32994
,I/jxcore-log( 5259): 2015-12-01T22:12:02.730Z SendDataConnector.js: CLIENT connected to 32994, error: null
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:02.731Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): incoming data from: /127.0.0.1, port: 32994
,I/BtToRequestSocket( 5259): Set local streams
,I/jxcore-log( 5259): 2015-12-01T22:12:02.736Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): rin ended ---------------------------;
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BTListenerThread( 5259): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6355
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:12:03.554Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/jxcore-log( 5259): 2015-12-01T22:12:03.935Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:03.939Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:03.945Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:03.979Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:03.982Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:03.986Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND FA.E5.62 p2p_dev_addr=FA.E5.62 pri_dev_type=10-0050F204-5   '50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6770 rs_disc_pending=0
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=0
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6770 rs_disc_pending=0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 36.0A.E2 p2p_dev_addr=36.0A.E2 pri_dev_type=10-0050F204-5   's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT2405
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT2405
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,I/jxcore-log( 5259): 2015-12-01T22:12:07.545Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
,D/dalvikvm(  746): GC_CONCURRENT freed 3479K, 56% free 24056K/54616K, paused 30ms+20ms, total 501ms
,I/PowerManagerService(  746): [PWL] Off : 600s ago
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/AmoledAdjustTimer(  746): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager(  746): waitForAlarm result :8
,D/LightsService(  746): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  746): getReportingMode :: sensor.mType = 5
D/Sensors (  746): LightSensor setDelay = 200000000
D/Sensors (  746): LightSensor setSensorDelay = 200000000
D/Sensors (  746): Light sensor flush: not enabled 0
D/Sensors (  746): LightSensor enable = 1
D/Sensors (  746): LightSensor enableSensor = 1
D/SensorManager(  746): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  746): LightSensor enable = 0
,D/Sensors (  746): LightSensor enableSensor = 0
,D/SensorManager(  746): unregisterListener ::   
D/LightsService(  746): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  746): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1951): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=0
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc692c rs_disc_pending=1
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/BluetoothBondStateMachine( 1951): Entering PendingCommandState State
,E/SMD     (  242): DCD ON
,D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): jangil::setProperties()
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
I/        ( 5259): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/IOP_DB_BT( 1951): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState receive service response
,I/        ( 5259): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btm  ( 1951): BTM_UseLeLink use le : 0
,E/bt-btif ( 1951): services_to_search = 3fffffff
,E/bt-btif ( 1951): ****************search UUID = 1200***********
,E/bt-btif ( 1951): services_to_search = 3ffffffe
,E/bt-btif ( 1951): ****************search UUID = 0100***********
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=0
,D/dalvikvm( 2184): GC_CONCURRENT freed 1883K, 41% free 11371K/19000K, paused 45ms+20ms, total 361ms
,D/dalvikvm( 2184): WAIT_FOR_CONCURRENT_GC blocked 307ms
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BTListenerThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3584
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-G900F_PT3584
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:12:12.648Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1951): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 5259): 2015-12-01T22:12:12.809Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:12.809Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/BluetoothBondStateMachine( 1951): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,I/jxcore-log( 5259): 2015-12-01T22:12:12.821Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:12.839Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:12.876Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 5259): 
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,I/jxcore-log( 5259): 2015-12-01T22:12:12.882Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 5259): 
,I/BtConnectorHelper( 5259): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToRequestSocket( 5259): Close server socket
,I/jxcore-log( 5259): 2015-12-01T22:12:12.919Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): ---- round done--------
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): do fake peer & start
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:12.924Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:12.926Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:12.927Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/BluetoothBondStateMachine( 1951): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 1951): isSecureModeOn:false
,D/HidService( 1951): getHidService(): returning com.android.bluetooth.hid.HidService@42dbdd18
,I/        ( 5259): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/HidService( 1951): Saved priority 7C:F9:0E:34:8A:A0 = -1
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
I/BluetoothBondStateMachine( 1951): StableState(): Entering Off State
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.UUID
D/GMFPReceiver( 5300): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5300): jangil::setProperties()
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/BTConnectToThread( 5259): Starting to connect
,I/        ( 5259): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/jxcore-log( 5259): 2015-12-01T22:12:13.012Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 5259): 
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,D/GMFPReceiver( 5300): jangil::printBTStatus()
,E/bt-btif ( 1951): RFCOMM connect
D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
I/chromium( 5259): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[123]}
,D/GMFPReceiver( 5300): ::::::::Wearable0001::false
,D/GMFPReceiver( 5300): ::::::::Wearable0002::false
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:12:13.879Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:13.883Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:13.894Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 5259): 
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6355
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/jxcore-log( 5259): 2015-12-01T22:12:14.133Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:14.483Z SendDataTCPServer.js: TCP/IP server has received 10216 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5   '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,I/jxcore-log( 5259): 2015-12-01T22:12:15.143Z SendDataTCPServer.js: TCP/IP server has received 16288 bytes of data
I/jxcore-log( 5259): 
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog(  746): !@Sync 21
,I/jxcore-log( 5259): 2015-12-01T22:12:15.708Z SendDataTCPServer.js: TCP/IP server has received 18312 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:15.723Z SendDataTCPServer.js: TCP/IP server has received 20336 bytes of data
I/jxcore-log( 5259): 
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
D/WifiP2pService(  746): InactiveState{ what=139265 }
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started peer discovery
,I/jxcore-log( 5259): 2015-12-01T22:12:16.311Z SendDataTCPServer.js: TCP/IP server has received 22360 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:16.342Z SendDataTCPServer.js: TCP/IP server has received 24384 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:12:16.916Z SendDataTCPServer.js: TCP/IP server has received 26408 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:16.921Z SendDataTCPServer.js: TCP/IP server has received 28432 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:16.933Z SendDataTCPServer.js: TCP/IP server has received 34504 bytes of data
I/jxcore-log( 5259): 
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:1f:c9:5e
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/jxcore-log( 5259): 2015-12-01T22:12:17.554Z SendDataTCPServer.js: TCP/IP server has received 36528 bytes of data
I/jxcore-log( 5259): 
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/AmoledAdjustTimer(  746): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5259): 2015-12-01T22:12:18.764Z SendDataTCPServer.js: TCP/IP server has received 38552 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND B6.A4.6B p2p_dev_addr=B6.A4.6B pri_dev_type=10-0050F204-5   '1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 5259): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService(  746): InactiveState{ what=139301 }
D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
I/        ( 5259): Added service request
,I/jxcore-log( 5259): 2015-12-01T22:12:19.375Z SendDataTCPServer.js: TCP/IP server has received 40576 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:19.385Z SendDataTCPServer.js: TCP/IP server has received 42600 bytes of data
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:12:19.948Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:19.950Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:19.954Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/        ( 5259): Started service discovery
,I/jxcore-log( 5259): 2015-12-01T22:12:20.845Z SendDataTCPServer.js: TCP/IP server has received 44624 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:20.851Z SendDataTCPServer.js: TCP/IP server has received 46648 bytes of data
I/jxcore-log( 5259): 
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5259): 2015-12-01T22:12:21.014Z SendDataTCPServer.js: TCP/IP server has received 48672 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:21.045Z SendDataTCPServer.js: TCP/IP server has received 52720 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:21.057Z SendDataTCPServer.js: TCP/IP server has received 54744 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:21.207Z SendDataTCPServer.js: TCP/IP server has received 56768 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 5259): 2015-12-01T22:12:21.528Z SendDataTCPServer.js: TCP/IP server has received 58792 bytes of data
I/jxcore-log( 5259): 
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/Tethering(  746): interfaceLinkStateChanged p2p0, false
D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:12:21.549Z SendDataTCPServer.js: TCP/IP server has received 60816 bytes of data
I/jxcore-log( 5259): 
,E/wpa_supplicant( 1947): P2P: Ignore unexpected GAS Initial Response from a2:39:f7:70:12:80
,I/jxcore-log( 5259): 2015-12-01T22:12:21.904Z SendDataTCPServer.js: TCP/IP server has received 62840 bytes of data
I/jxcore-log( 5259): 
,E/wpa_supplicant( 1947): P2P: Ignore unexpected GAS Initial Response from a2:39:f7:70:12:80
,E/wpa_supplicant( 1947): P2P: Ignore unexpected GAS Initial Response from a2:39:f7:70:12:80
,I/jxcore-log( 5259): 2015-12-01T22:12:21.943Z SendDataTCPServer.js: TCP/IP server has received 64864 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:22.001Z SendDataTCPServer.js: TCP/IP server has received 66888 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:22.447Z SendDataTCPServer.js: TCP/IP server has received 68912 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:22.454Z SendDataTCPServer.js: TCP/IP server has received 72960 bytes of data
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:12:23.214Z SendDataTCPServer.js: TCP/IP server has received 74984 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:23.252Z SendDataTCPServer.js: TCP/IP server has received 77008 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:23.337Z SendDataTCPServer.js: TCP/IP server has received 79032 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:23.346Z SendDataTCPServer.js: TCP/IP server has received 83080 bytes of data
I/jxcore-log( 5259): 
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,I/jxcore-log( 5259): 2015-12-01T22:12:23.770Z SendDataTCPServer.js: TCP/IP server has received 85104 bytes of data
I/jxcore-log( 5259): 
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,I/jxcore-log( 5259): 2015-12-01T22:12:24.229Z SendDataTCPServer.js: TCP/IP server has received 87128 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.326Z SendDataTCPServer.js: TCP/IP server has received 89152 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.332Z SendDataTCPServer.js: TCP/IP server has received 91176 bytes of data
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/jxcore-log( 5259): 2015-12-01T22:12:24.402Z SendDataTCPServer.js: TCP/IP server has received 93200 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.423Z SendDataTCPServer.js: TCP/IP server has received 95224 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.460Z SendDataTCPServer.js: TCP/IP server has received 97248 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.741Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.956Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:24.957Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 36.0A.E2 p2p_dev_addr=36.0A.E2 pri_dev_type=10-0050F204-5   's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/AmoledAdjustTimer(  746): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/SMD     (  242): DCD ON
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 5259): 2015-12-01T22:12:29.961Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:29.962Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:29.965Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:29.967Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 5259): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[123]}
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,E/SMD     (  242): DCD ON
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND EA.28.A3 p2p_dev_addr=EA.28.A3 pri_dev_type=10-0050F204-5   'e3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:12:36.116Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:36.117Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:36.119Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
,I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/jxcore-log( 5259): 2015-12-01T22:12:36.328Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
I/BtToSocketBase( 5259): Close bt in
I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/AmoledAdjustTimer(  746): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,I/        ( 5259): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/        ( 5259): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 5259): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: S5-1
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 5259): 2015-12-01T22:12:41.122Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:41.123Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,E/SMD     (  242): DCD ON
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=139307 }
D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): InactiveState{ what=139265 }
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/Watchdog(  746): !@Sync 22
,I/jxcore-log( 5259): 2015-12-01T22:12:46.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:46.128Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:46.129Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:46.132Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 5259): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[122]}
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/SS      ( 5259): Found 15 peers.
,I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d,
,I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d,
,I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80,
,I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac,
,I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62,
,I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c,
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
,E/SMD     (  242): DCD ON
,D/WifiP2pManager( 5259): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService(  746): InactiveState{ what=139301 }
D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  746): P2pEnabledState add service request
I/        ( 5259): Added service request
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started service discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/AmoledAdjustTimer(  746): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/BatteryService(  746): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5   'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5   '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  746): InactiveState{ what=147494 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147494 }
,I/        ( 5259): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 5259): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
,D/WifiP2pService(  746): P2pEnabledState receive service response
I/BtConnectorHelper( 5259): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 36.0A.E2 p2p_dev_addr=36.0A.E2 pri_dev_type=10-0050F204-5   's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/dalvikvm(  746): GC_CONCURRENT freed 3487K, 56% free 24174K/54616K, paused 32ms+19ms, total 488ms
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147477 }
D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiDisplayController(  746): Received list of peers.
,D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  242): DCD ON
,D/WifiP2pService(  746): InactiveState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  746): P2pEnabledState clear service request
,I/        ( 5259): Cleared service requests
D/WifiP2pService(  746): InactiveState{ what=139265 }
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,I/        ( 5259): Started peer discovery
,I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 02.E0.6D p2p_dev_addr=02.E0.6D pri_dev_type=10-0050F204-5   'ni-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1947): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5   '' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=147477 }
,D/WifiP2pService(  746): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  746): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  746): DefaultState{ what=139283 }
D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62,, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
,D/WifiP2pService(  746): InactiveState{ what=139283 }
,I/SS      ( 5259): Found 15 peers.
,D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
I/SS      ( 5259): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 5259): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 5259): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 5259): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 5259): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 5259): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 5259): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 5259): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 5259): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 5259): Peer(10): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 5259): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 5259): Peer(12): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 5259): Peer(13): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 5259): Peer(14): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 5259): Peer(15): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiDisplayController(  746): Received list of peers.
D/WifiDisplayController(  746):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_1950, deviceAddress: b6:ce:f6:ad:a4:6b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: XT1039_8c05, deviceAddress: f4:f1:e1:5c:43:c8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Android_63cc, deviceAddress: 82:01:84:6b:e8:5d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: WFD enabled: trueWFD DeviceInfo: 16, WFD CtrlPort: 7236, WFD MaxThroughput: 50, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Thali Test's G2, deviceAddress: 36:fc:ef:de:0a:e2, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: S5mini-1, deviceAddress: 02:f4:6f:30:e0:6d, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   D,evice: Android_50a5, deviceAddress: fa:cf:c5:d9:e5:62, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  746):   Device: Note3-1, deviceAddress: ea:50:8b:de:28:a3, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  746): InactiveState{ what=139283 }
D/WifiP2pService(  746): P2pEnabledState{ what=139283 }
D/WifiP2pService(  746): DefaultState{ what=139283 }
D/WifiP2pService(  746): InactiveState{ what=139301 }
D/WifiP2pService(  746): P2pEnabledState{ what=139301 }
D/WifiP2pManager( 5259): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 5259): Added service request
D/WifiP2pService(  746): P2pEnabledState add service request
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,E/wpa_supplicant( 1947): Cmd 35609 not handled
,D/WifiP2pService(  746): InactiveState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  746): P2pEnabledState discover services
,I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
,D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,I/        ( 5259): Started service discovery
,D/AmoledAdjustTimer(  746): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
I/wpa_supplicant( 1947): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  242): DCD ON
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:12:59.005Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:59.007Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:12:59.008Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,I/wpa_supplicant( 1947): P2P-FIND-STOPPED 
,E/wpa_supplicant( 1947): Cmd 35609 not handled
D/WifiP2pService(  746): InactiveState{ what=147493 }
D/WifiP2pService(  746): P2pEnabledState{ what=147493 }
D/WifiP2pService(  746): discovery change broadcast false
,I/        ( 5259): Discovery state changed to Stopped.
D/WifiP2pService(  746): InactiveState{ what=139265 }
,D/WifiP2pService(  746): P2pEnabledState{ what=139265 }
I/WifiService(  746): setWifiEnabled: true pid=746, uid=1000
,D/WifiStateMachine(  746): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative(  746): callSECApiBoolean - ID [13]
D/WifiService(  746): WiFi Enabled with p2p -> Stop Scan, Stop Assoc
,D/Tethering(  746): interfaceLinkStateChanged p2p0, false
,D/Tethering(  746): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 1947): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  746): discovery change broadcast true
I/        ( 5259): Started peer discovery
,I/        ( 5259): Discovery state changed to Started.
,V/AlarmManager(  746): waitForAlarm result :8
,V/AlarmManager(  746): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  746): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  746): <AppSync3 Whitelist>
,V/AlarmManager(  746): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: S5-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,E/SMD     (  242): DCD ON
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BTListenerThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3584
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-G900F_PT3584
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:13:02.100Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,I/jxcore-log( 5259): 2015-12-01T22:13:02.678Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:02.726Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:02.797Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:02.848Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:02.851Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:02.978Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:04.012Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:04.014Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,I/wpa_supplicant( 1947): P2P: p2p_find command is fail.
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,E/SMD     (  242): DCD ON
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btm  ( 1951): tBTM_SEC_DEV:0x77fc6ca4 rs_disc_pending=1
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTListenerThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT2405
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-N910C_PT2405
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:13:08.404Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,D/AmoledAdjustTimer(  746): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 5259): 2015-12-01T22:13:08.812Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:08.961Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:08.969Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:08.973Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:09.020Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:09.021Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:09.023Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:09.025Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 5259): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[129]}
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [b0:c5:59:3f:75:69]: 7, f, 2205
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:13:09.403Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:09.406Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:09.407Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToSocketBase( 5259): Close bt socket
,I/jxcore-log( 5259): 2015-12-01T22:13:12.877Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/jxcore-log( 5259): 2015-12-01T22:13:14.411Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:14.411Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,E/Watchdog(  746): !@Sync 23
,E/SMD     (  242): DCD ON
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/AmoledAdjustTimer(  746): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
,D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT2405
I/BtToSocketBase( 5259): Stop ReceivingThread
,I/BtToSocketBase( 5259): Stop SendingThread
,I/BtToSocketBase( 5259): Close local in
,I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT2405
,I/BtToSocketBase( 5259): Close LocalOutputStream
,I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt in
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/BtToSocketBase( 5259): Close bt out
,I/BtToSocketBase( 5259): Close bt socket
,I/jxcore-log( 5259): 2015-12-01T22:13:19.119Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:19.414Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:19.415Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:19.417Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:19.418Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 5259): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[123]}
,E/SMD     (  242): DCD ON
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:13:20.027Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:20.029Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:20.048Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:20.059Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): ---- round done--------
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 5259): 
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936]
,I/jxcore-log( 5259): do fake peer & start
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:20.073Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:20.076Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:20.078Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 5259): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 5259): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: Connection to B0:C5:59:3F:75:69 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[123]}
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1951): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:13:21.881Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:21.884Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:21.885Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,E/SMD     (  242): DCD ON
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: S5-1
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTListenerThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3584
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-G900F_PT3584
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 5259): --DoOneRunRound started
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,I/jxcore-log( 5259): 2015-12-01T22:13:24.279Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note4-1
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,I/jxcore-log( 5259): 2015-12-01T22:13:24.815Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:24.837Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:24.841Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:24.848Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:24.850Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:24.854Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
W/ProcessCpuTracker(  746): Skipping unknown process pid 6112
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: A3-1
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:13:26.888Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:26.889Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/PowerManagerService(  746): [PWL] Off : 680s ago
,D/AmoledAdjustTimer(  746): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [e0:db:10:14:e2:c0]: 7, f, 610c
,D/BatteryService(  746): stay LED for fully charged
,D/UiModeManager(  746): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,E/bt-btif ( 1951): RFCOMM: PORT_SUCCESS
,I/BTListenerThread( 5259): we got incoming connection
,I/BTHandshakeSocketThread( 5259): Creating BTHandshakeSocketThread
,I/BTListenerThread( 5259): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread started
,I/BTListenerThread( 5259): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 5259): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 5259): MESSAGE_WRITE 82 bytes.
,I/HS      ( 5259): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT2405
,I/BTHandshakeSocketThread( 5259): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 5259): Starting the connected thread incoming : true, samsung-SM-N910C_PT2405
,I/BtToSocketBase( 5259): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 5259): Creating BTConnectedThread
,D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
I/BtConnectorHelper( 5259): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 5259): --DoOneRunRound started
,I/jxcore-log( 5259): 2015-12-01T22:13:31.304Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 5259): 
,I/BtToRequestSocket( 5259): LocalHost address: localhost/127.0.0.1, port: 41366
,I/BtToRequestSocket( 5259): --DoOneRunRound ended
,E/SMD     (  242): DCD ON
,I/jxcore-log( 5259): 2015-12-01T22:13:31.754Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.763Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.769Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.778Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.893Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.894Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.895Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:31.897Z SendDataConnector.js: do connect now
I/jxcore-log( 5259): 
,I/        ( 5259): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 5259): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 5259): Starting to connect
,D/BluetoothUtils( 5259): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 5259): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 1951): RFCOMM connect
,D/BTIF_SOCK( 1951): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/BluetoothSocket( 5259): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[131]}
,D/IOP_DB_BT( 1951): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 1951): db_query_execute: result 1
,D/        ( 1951): remote version info [08:ec:a9:50:75:41]: 7, f, 2205
,E/bt-btif ( 1951): BTA_JV_DISCOVERY_COMP_EVT (error code = 1)
,E/bt-btif ( 1951): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 5259): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_CONNECTED
,I/CONNEC  ( 5259): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 5259): 2015-12-01T22:13:33.368Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:33.371Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 5259): 
,I/jxcore-log( 5259): 2015-12-01T22:13:33.374Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 5259): 
,D/KeyguardViewMediator( 1068): isGear1: device is not B1!
,V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.NAME_CHANGED
,I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 2184): Bluetooth Device Name: A3-1
,D/UserAnalysis.CarAnalyzer( 5863): Create SecureDbHelper
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
,TIME-OUT KILL (timeout was 600000ms),E/SMD     (  242): DCD ON
E/bt-btif ( 1951): RFCOMM: PORT_FAILURE
I/BtToSocketBase( 5259): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
I/BtToSocketBase( 5259): Stop ReceivingThread
I/BtToSocketBase( 5259): Stop SendingThread
I/BtToSocketBase( 5259): Close local in
I/BtToSocketBase( 5259): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 5259): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
I/BtToSocketBase( 5259): Close LocalOutputStream
I/BtToSocketBase( 5259): Close localHostSocket
I/BtToSocketBase( 5259): Close bt in
I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt in
I/BtToSocketBase( 5259): Close bt out
I/BtToSocketBase( 5259): Close bt socket
I/BtToSocketBase( 5259): Close bt socket
I/jxcore-log( 5259): 2015-12-01T22:13:35.322Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 5259): 
E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/SMD     (  242): DCD ON
V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
D/KeyguardViewMediator( 1068): isGear1: device is not B1!
E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
I/BluetoothClassifier( 2184): Bluetooth Device Name: A3-1
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
I/jxcore-log( 5259): 2015-12-01T22:13:38.391Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
I/jxcore-log( 5259): 2015-12-01T22:13:38.392Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 5259): 
D/AmoledAdjustTimer(  746): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
D/btif_config_util( 1951): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/AndroidRuntime( 6123): 
D/AndroidRuntime( 6123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6123): CheckJNI is OFF
D/AndroidRuntime( 6123): setted country_code = Poland
D/AndroidRuntime( 6123): setted countryiso_code = PL
D/AndroidRuntime( 6123): setted sales_code = XEO
D/AndroidRuntime( 6123): readGMSProperty: start
D/AndroidRuntime( 6123): readGMSProperty: already setted!!
D/AndroidRuntime( 6123): readGMSProperty: end
D/AndroidRuntime( 6123): addProductProperty: start
D/dalvikvm( 6123): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6123): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6123): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6123): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6123): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6123): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6123): failed to load memtrack module: -2
D/dalvikvm( 6123): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6123): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  746): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  746): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  746): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  746): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  746): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  746): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  746): START PACKAGE DELETE: observer{1154650528}
D/PackageManager(  746): pkg{<packageName>}
D/PackageManager(  746): user{0}
D/PackageManager(  746): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  746): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  746): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  746): getApplicationUninstallationEnabled
D/ApplicationPolicy(  746): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  746): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  746): [MSG] DELETE_PACKAGE_AS_USER
E/bt-btm  ( 1951): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 1951): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 1951): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 1951): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 1951): db_query_execute: result 1
D/KeyguardViewMediator( 1068): Received android.bluetooth.device.action.ACL_DISCONNECTED
D/KeyguardViewMediator( 1068): isGear1: device is not B1!
V/BluetoothEventManager( 1311): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1311): ACTION_ACL_DISCONNECTED
I/BTConnectionReceiver( 2184): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 2184): Bluetooth Device Name: S5-1
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
D/PackageManager(  746): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  746): Killing 5259:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
D/GKI_LINUX( 1951): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
I/SurfaceFlinger(  248): id=16 Removed NainActivit (7/12)
E/bt-btif ( 1951): bta_jv_rfcomm_stop_server
D/GKI_LINUX( 1951): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
I/SurfaceFlinger(  248): id=16 Removed NainActivit (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/WindowState(  746): WIN DEATH: Window{43dbf310 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  248): id=16 Removed NainActivit (-2/12)
D/PackageManager(  746): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2184): GC_EXPLICIT freed 860K, 41% free 11252K/19000K, paused 10ms+6ms, total 49ms
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader(  746): Reconfiguring input devices.  changes=0x00000010
D/PackageManager(  746): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1405): GC_EXPLICIT freed 4281K, 48% free 10017K/19000K, paused 5ms+5ms, total 79ms
D/QuickConnect[1.1][2] ( 3350): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/BatteryService(  746): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  746): stay LED for fully charged
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "sms"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6150): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6150):  
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "smsto"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 1211): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 6150): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6150):  
I/SELinux ( 6150):  
I/SELinux ( 6150): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6150): >>>>> Normal User
E/dalvikvm( 6150): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  746): GC_EXPLICIT freed 2779K, 56% free 24178K/54616K, paused 7ms+13ms, total 158ms
D/TimaKeyStoreProvider( 6150): in addTimaSignatureService
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "mms"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6150): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6150): Added TimaKesytore provider
D/RCPManagerService(  746): PackageReceiver onReceive()
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "mmsto"
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/HarmonyEASService(  746): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/EnterpriseDeviceManagerService(  746): Package has changed for user 0
D/EnterpriseDeviceManagerService(  746): Admin package name: com.google.android.gms
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "sms"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/BluetoothAdapterService(1121450760)( 1951): Get Bonded Devices being called
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "smsto"
I/SurfaceFlinger(  248): id=19 createSurf (1x1),2 flag=404, CatteryCove
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "mms"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "mmsto"
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
E/SMD     (  242): DCD ON
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=6150, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 6150): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6150): ELMEngine.ELMEngine( context ).
D/elm:14132( 6150): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6150): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 6150): ElmAgentService : onCreate()
D/elm:14132( 6150): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6150): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6150): MDMBridge.getInstance()
D/elm:14132( 6150): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6150): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6165): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6165):  
D/elm:14132( 6150): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/BackupManagerService(  746): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  746): removePackageParticipantsLocked: uid=10179 #1
D/BatteryService(  746): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/HeadsetService( 1951): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1951): Disconnected process message: 10
D/elm:14132( 6150): ElmAgentService : onDestroy().
I/ActivityManager(  746): Killing 5026:com.android.defcontainer/u0a6 (adj 15): empty #43
I/SELinux ( 6165): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6165):  
I/SELinux ( 6165):  
I/SELinux ( 6165): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6165): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6165): >>>>> Normal User
E/dalvikvm( 6165): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6165): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/UiModeManager(  746): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 6165): in addTimaSignatureService
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 6165): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6165): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm(  746): GC_EXPLICIT freed 1101K, 56% free 24229K/54616K, paused 6ms+24ms, total 293ms
D/PackageManager(  746): delete sourFile : 
D/PackageManager(  746): delete native library directory: 
D/PackageManager(  746): return delete result to caller: 1154650528
D/AndroidRuntime( 6123): Shutting down VM
D/PackageManager(  746): returnCode: 1
D/dalvikvm( 6123): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "sms"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "smsto"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "mms"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  746):   Action: "android.intent.action.SENDTO"
I/PackageManager(  746):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  746):   Scheme: "mmsto"
I/PackageManager(  746): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  746): Permission Denial: getCurrentUser() from pid=6165, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/Launcher( 1260): onRestart, Launcher: 1122052296
D/Launcher( 1260): onStart, Launcher: 1122052296
D/Launcher.HomeView( 1260): onStart
D/dalvikvm( 6165): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42d6cb60, skipping init
I/SecureStorage( 6165): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6165): [INFO]: SPID(0x00000000)This device supports Secure Storage
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage(  318): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6165
I/SecureStorage(  318): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6165): [INFO]: SPID(0x00000000)SS Daemon is running
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1449): [237392/5] SurfaceWidget drawing first frame
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SurfaceFlinger(  248): id=20 createSurf (720x1280),1 flag=4, Mauncher
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6165): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  318): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6165
I/SecureStorage(  318): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  746): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  746): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  746): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
E/bt-btif ( 1951): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
D/InputReader(  746): Processing first event
D/SSRMv2:SIOP(  746): SIOP:: AP = 300, Delta = 0
W/ApplicationsProvider( 1405): Could not fetch usage stats
W/ApplicationsProvider( 1405): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1405): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1405): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1405): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1405): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1405): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1405): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1405): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
