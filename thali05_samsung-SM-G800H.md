#### Test 50650278b1aec71_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5111): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5111):  
--------- beginning of /dev/log/system
I/ActivityManager(  731): Killing 3884:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,D/dalvikvm(  250): GC_EXPLICIT freed 46K, 49% free 9508K/18424K, paused 4ms+2ms, total 35ms
I/SELinux ( 5111): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5111):  
I/SELinux ( 5111):  
I/SELinux ( 5111): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5111): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5111): >>>>> Normal User
E/dalvikvm( 5111): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5111): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18424K, paused 2ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5111): in addTimaSignatureService
D/TimaKeyStoreProvider( 5111): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5111): Added TimaKesytore provider
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18424K, paused 2ms+2ms, total 19ms
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5111, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5111): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5111): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  731): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
I/SA      ( 3958): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 3958): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 3958): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4258): loadAuthorityPref(): sEnableAuthority = true
D/AndroidRuntime( 5124): 
D/AndroidRuntime( 5124): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5124): CheckJNI is OFF
D/AndroidRuntime( 5124): setted country_code = Poland
D/AndroidRuntime( 5124): setted countryiso_code = PL
D/AndroidRuntime( 5124): setted sales_code = XEO
D/AndroidRuntime( 5124): readGMSProperty: start
D/AndroidRuntime( 5124): readGMSProperty: already setted!!
D/AndroidRuntime( 5124): readGMSProperty: end
D/AndroidRuntime( 5124): addProductProperty: start
D/dalvikvm( 5124): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5124): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5124): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5124): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5124): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/IcingCorporaProvider( 2178): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5148): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5148):  
I/ActivityManager(  731): Killing 3896:com.samsung.klmsagent/u0a18 (adj 15): empty #43
I/SELinux ( 5148): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5148):  
I/SELinux ( 5148):  
I/SELinux ( 5148): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5148): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5148): >>>>> Normal User
E/dalvikvm( 5148): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5148): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5148): in addTimaSignatureService
D/TimaKeyStoreProvider( 5148): Cannot add TimaSignature Service, License check Failed
E/memtrack( 5124): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5124): failed to load memtrack module: -2
D/ActivityThread( 5148): Added TimaKesytore provider
D/dalvikvm( 2178): GC_CONCURRENT freed 6483K, 40% free 11205K/18424K, paused 6ms+4ms, total 126ms
D/dalvikvm( 2178): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/dalvikvm( 5124): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5148, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 5148): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 5161): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5161):  
I/ActivityManager(  731): Killing 4182:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/AndroidRuntime( 5124): Calling main entry com.android.commands.am.Am
I/IcingCorporaProvider( 2178): UpdateCorporaTask done [took 239 ms] updated apps [took 239 ms] 
I/SELinux ( 5161): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5161):  
I/SELinux ( 5161):  
I/SELinux ( 5161): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5161): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5161): >>>>> Normal User
E/dalvikvm( 5161): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5161): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5161): in addTimaSignatureService
D/TimaKeyStoreProvider( 5161): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5161): Added TimaKesytore provider
V/ApplicationPolicy(  731): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  731): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  731): mDVFSHelper.acquire()
I/SELinux ( 5175): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5175):  
D/LockPatternUtils( 1066): isPcwEnable = null
D/AndroidRuntime( 5124): Shutting down VM
D/dalvikvm( 5124): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 5175): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5175):  
I/SELinux ( 5175):  
I/SELinux ( 5175): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5175): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5175): >>>>> Normal User
E/dalvikvm( 5175): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5175): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5175): in addTimaSignatureService
D/TimaKeyStoreProvider( 5175): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5175): Added TimaKesytore provider
D/LockPatternUtils( 1066): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2105): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2105): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (8/12)
D/SurfaceWidgetView( 1252): destroyHardwareResources():1127378496
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  249): id=9 Removed Mauncher (7/11)
I/SurfaceFlinger(  249): id=9 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/AmoledAdjustTimer(  731): prevTemp = 302, currTemp = 302, prevStep = 5, currStep = 5
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1252): onTrimMemory. Level: 20
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5175, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5161, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5175, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5175): Binding Chromium to the background looper Looper (main, tid 1) {423f8158}
I/chromium( 5175): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5175): Initializing chromium process, renderers=0
W/chromium( 5175): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5175): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5175): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5175): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5175): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5175): Remote Branch: 
I/Adreno-EGL( 5175): Local Patches: 
I/Adreno-EGL( 5175): Reconstruct Branch: 
,I/dalvikvm( 5175): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5175): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5175): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5175): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5175): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5175): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5175): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5175): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5175): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5175): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5175): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5175): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5175): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5175): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5175): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5175): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5175): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5175): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5175): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5175): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5175): Enabling debug mode 0
W/AwContents( 5175): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  731): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  731): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  731): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5216):  
E/SMD     (  243): DCD ON
W/GAV2    ( 5161): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5216):  
I/SELinux ( 5216):  
I/SELinux ( 5216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5216): >>>>> Normal User
E/dalvikvm( 5216): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5216): in addTimaSignatureService
D/TimaKeyStoreProvider( 5216): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5216): Added TimaKesytore provider
D/PackageIntentReceiver( 5216): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5216): Not GearManger package! 
I/SELinux ( 5237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5237):  
I/ActivityManager(  731): Killing 3909:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5237):  
I/SELinux ( 5237):  
I/SELinux ( 5237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5237): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5237): >>>>> Normal User
E/dalvikvm( 5237): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5237): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5237): in addTimaSignatureService
D/TimaKeyStoreProvider( 5237): Cannot add TimaSignature Service, License check Failed
D/JsMessageQueue( 5175): Set native->JS mode to OnlineEventsBridgeMode
D/ActivityThread( 5237): Added TimaKesytore provider
D/MagazineService Version( 5237): Magazine-Channel: 13
D/MagazineService Version( 5237): Magazine-Provider: 13
D/MagazineService Version( 5237): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5237): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5237): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5237, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5237): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5251):  
D/MagazineService::MagazineService( 5237): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  731): Killing 4294:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
D/dalvikvm( 5175): Trying to load lib /data/app-lib/com.test.thalitest-17/libjxcore.so 0x4271eec8
D/dalvikvm( 5175): Added shared lib /data/app-lib/com.test.thalitest-17/libjxcore.so 0x4271eec8
D/jxcore_app_log( 5175): JniHelper::setJavaVM(0x419e64f8), pthread_self() = 1942916864
D/JX-Cordova( 5175): jxcore cordova android initializing
I/dalvikvm( 5175): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5175): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5175): VFY: replacing opcode 0x6e at 0x0045
W/GAV2    ( 5161): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/SELinux ( 5251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5251):  
I/SELinux ( 5251):  
I/SELinux ( 5251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5251): >>>>> Normal User
E/dalvikvm( 5251): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  731): Killing 1336:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/TimaKeyStoreProvider( 5251): in addTimaSignatureService
D/TimaKeyStoreProvider( 5251): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5251): Added TimaKesytore provider
,I/SELinux ( 5265): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5265):  
I/ActivityManager(  731): Killing 4308:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5265): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5265):  
I/SELinux ( 5265):  
,I/SELinux ( 5265): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5265): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5265): >>>>> Normal User
,E/dalvikvm( 5265): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5265): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5265): in addTimaSignatureService
V/AlarmManager(  731): waitForAlarm result :4
,D/TimaKeyStoreProvider( 5265): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5265): Added TimaKesytore provider
V/AlarmManager(  731): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 5175): GC_CONCURRENT freed 4924K, 31% free 12764K/18424K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 5175): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 5175): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5265, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5265): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5278): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5278):  
I/ActivityManager(  731): Killing 4321:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5278): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5278):  
I/SELinux ( 5278):  
,I/SELinux ( 5278): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5278): >>>>> Normal User
,E/dalvikvm( 5278): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5278): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5278): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5278): Added TimaKesytore provider
,I/ActivityManager(  731): Killing 3504:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/PackageBroadcastService( 1751): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1751): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService(  731): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  tag : ACTIVITY_RESUME_BOOSTER@9
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1751): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1751): Submit a task: h
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1751): Processing package: com.test.thalitest
,I/PeopleContactsSync( 1751): CP2 sync disabled
,D/Finsky  ( 3648): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/GassUtils( 1751): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/h       ( 1751): Found info for package com.test.thalitest in db.
W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,I/dalvikvm( 1751): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
,W/dalvikvm( 1751): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1751): VFY: replacing opcode 0x6e at 0x000e
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,D/dalvikvm( 1751): GC_CONCURRENT freed 1783K, 36% free 11806K/18424K, paused 10ms+13ms, total 100ms
,W/SQLiteConnectionPool( 1751): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,D/FactoryTest( 4666): Not factory mode
,D/FactoryTest( 4666): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4666): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4666): still no open session command from host, so toast
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
V/ApplicationPolicy(  731): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,D/dalvikvm( 5175): GC_FOR_ALLOC freed 4696K, 26% free 15766K/21220K, paused 36ms, total 42ms
D/CustomFrequencyManagerService(  731): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  731): mDVFSHelper.acquire()
,D/LockPatternUtils( 1066): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2105): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2105): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1066): isPcwEnable = null
,E/MTPRx   ( 4666): started activity for popup
,E/SettingsReceiverActivity( 4666): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4666): dev.kiessupport is : TRUE
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/VacuumService( 1316): Vacuum at: now=1449595687988 tag=VacuumService
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4666): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4666): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4666): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4666): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4666): Remote Branch: 
I/Adreno-EGL( 4666): Local Patches: 
I/Adreno-EGL( 4666): Reconstruct Branch: 
,I/HWUI    ( 4666): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4666): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  731): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  731): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/CustomFrequencyManagerService(  731): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 5175): GC_FOR_ALLOC freed 5053K, 30% free 16772K/23892K, paused 34ms, total 34ms
,I/dalvikvm-heap( 5175): Grow heap (frag case) to 21.441MB for 2459024-byte allocation
,D/dalvikvm( 5175): GC_FOR_ALLOC freed 3768K, 34% free 17453K/26296K, paused 31ms, total 31ms
,D/dalvikvm( 5175): GC_FOR_ALLOC freed 1224K, 34% free 17358K/26296K, paused 28ms, total 31ms
,W/jxcore-log( 5175): Initializing JXcore engine
,W/jxcore-log( 5175): JXcore engine is ready
,W/jxcore-log( 5175): Starting JXcore engine
,D/CustomFrequencyManagerService(  731): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 731  tag : ACTIVITY_RESUME_BOOSTER@9
,W/jxcore-log( 5175): Platform android
W/jxcore-log( 5175): 
,W/jxcore-log( 5175): Process ARCH arm
W/jxcore-log( 5175): 
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
D/BatteryService(  731): stay LED for fully charged
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/jxcore-log( 5175): JXcore Cordova bridge is ready!
I/jxcore-log( 5175): 
,W/jxcore-log( 5175): JXcore engine is started
,I/chromium( 5175): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5175): Error!: missing ) after argument list
E/jxcore  ( 5175): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5175): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  731): Killing 4349:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,I/SurfaceFlinger(  249): id=17 Removed NainActivit (7/12)
,I/SurfaceFlinger(  249): id=17 Removed NainActivit (-2/12)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/SSRMv2:SIOP(  731): SIOP:: AP = 330, Delta = 10
,I/GAV2    ( 5161): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 302, currTemp = 303, prevStep = 5, currStep = 5
,I/HarmonyEASService(  731): Updating for all 1
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  731): SIOP:: AP = 320, Delta = -10
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  731): prevTemp = 303, currTemp = 303, prevStep = 5, currStep = 5
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): waitForAlarm result :4
,V/AlarmManager(  731): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4011): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4011): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4011): Breath 90184 latestRequest time : 1449595619741 current time : 1449595709926
,E/SMD     (  243): DCD ON
,D/Finsky  ( 3648): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3648): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRMv2:SIOP(  731): SIOP:: AP = 310, Delta = -10
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 303, currTemp = 302, prevStep = 5, currStep = 5
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = -10
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 302, currTemp = 301, prevStep = 5, currStep = 5
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 5
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  731): prevTemp = 301, currTemp = 299, prevStep = 5, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,D/Headlines( 4011): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4011): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4011): Breath 120036 latestRequest time : 1449595619741 current time : 1449595739780
,D/Headlines( 4011): stop 
,D/Headlines( 4011): Breath.onDestroy : 
,I/ActivityManager(  731): Killing 4364:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 6
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 140s ago
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/ClearcutLoggerApiImpl( 1316): disconnect managed GoogleApiClient
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 7
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 180s ago
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/dalvikvm(  731): GC_CONCURRENT freed 3735K, 58% free 23671K/55152K, paused 22ms+45ms, total 496ms
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 8
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,E/SMD     (  243): DCD ON
D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 9
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  731): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  731): initializing...
,I/TLC_TIMA_PKM_initialize(  731): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  731): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  731): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  731): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  731): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  731): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  731): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  731): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  731): App is not loaded in QSEE
,D/QSEECOMAPI: (  731): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  731): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  731): Trustlet response is completed
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  731): !@Sync 10
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 275s ago
,V/AlarmManager(  731): waitForAlarm result :4
,V/AlarmManager(  731): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SMD     (  243): DCD ON
,I/SELinux ( 5372): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5372):  
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5372): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5372):  
I/SELinux ( 5372):  
,I/SELinux ( 5372): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5372): >>>>> Normal User
E/dalvikvm( 5372): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5372): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5372): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5372): Added TimaKesytore provider
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1252): destroyHardwareResources():1127378496
,D/AmoledAdjustTimer(  731): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=19 createSurf (1x1),2 flag=404, CatteryCove
,D/Launcher( 1252): onRestart, Launcher: 1115445024
,D/Launcher( 1252): onStart, Launcher: 1115445024
,D/Launcher.HomeView( 1252): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidget.Renderer( 1449): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=20 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5372, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  731): Killing 4388:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 11
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 12
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  731): [PWL] Off : 330s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 13
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  731): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 14
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AmoledAdjustTimer(  731): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  731): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  731): [PWL] Off : 390s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 15
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 16
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): stay LED for fully charged
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 455s ago
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 17
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 18
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 19
,I/PowerManagerService(  731): [PWL] Off : 525s ago
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 20
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 21
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  731): [PWL] Off : 600s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 22
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  731): GC_CONCURRENT freed 3620K, 58% free 23498K/54676K, paused 20ms+39ms, total 426ms
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 23
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,E/SMD     (  243): DCD ON
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  731): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  731): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  731): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 24
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-15, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  731): [PWL] Off : 680s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  731): !@Sync 25
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 26
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 27
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  731): [PWL] Off : 765s ago
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 28
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 29
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  731): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  731): !@Sync 30
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  731): [PWL] Off : 855s ago
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 31
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :4
,I/SensorManagerA(  731): getReportingMode :: sensor.mType = 5
,D/Sensors (  731): LightSensor setDelay = 200000000
,D/LightsService(  731): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  731): LightSensor setSensorDelay = 200000000
D/Sensors (  731): Light sensor flush: not enabled 0
D/Sensors (  731): LightSensor enable = 1
D/Sensors (  731): LightSensor enableSensor = 1
D/SensorManager(  731): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  731): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  731): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  731): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  731): LightSensor enable = 0
D/Sensors (  731): LightSensor enableSensor = 0
,D/SensorManager(  731): unregisterListener ::   
D/LightsService(  731): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1751): Aggregate from 1449594439202 (log), 1449594439202 (data)
,D/UdcCache:FPQuery( 1751): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1316): GC_EXPLICIT freed 1588K, 40% free 11104K/18424K, paused 48ms+11ms, total 267ms
,D/ConnectivityService(  731): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/GetConfigurationSnapshotOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1316): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1316): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 1316): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1316): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1316): VFY: replacing opcode 0x6e at 0x0033
,I/System.out( 1316): Thread-121(HTTPLog):isShipBuild true
,I/System.out( 1316): Thread-121(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1316):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1316): no corresponding serverToken: com.google.android.gms.playlog.uploader
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 32
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 33
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 950s ago
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 34
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 35
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,W/ProcessCpuTracker(  731): Skipping unknown process pid 5593
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm(  731): GC_CONCURRENT freed 3381K, 57% free 23518K/54456K, paused 22ms+39ms, total 428ms
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 36
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 1050s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 37
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 38
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 39
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 40
,I/PowerManagerService(  731): [PWL] Off : 1155s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 41
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 42
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 43
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  731): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  731): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager(  731): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  731): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  731): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 44
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 45
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  731): !@Sync 46
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 47
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 1380s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 48
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 49
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SMD     (  243): DCD ON
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 50
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 51
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/dalvikvm(  731): GC_CONCURRENT freed 3436K, 57% free 23512K/54456K, paused 19ms+36ms, total 417ms
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 1500s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 52
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 53
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 54
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 55
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 1625s ago
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 56
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,E/SMD     (  243): DCD ON
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 57
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 58
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 59
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 60
,I/PowerManagerService(  731): [PWL] Off : 1755s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 61
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  731): Prepared write state in 100ms
,I/ProcessStatsService(  731): Prepared write state in 99ms
,I/ProcessStatsService(  731): Pruning old procstats: /data/system/procstats/state-2015-12-08-01-13-32.bin
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :4
,I/SensorManagerA(  731): getReportingMode :: sensor.mType = 5
,D/Sensors (  731): LightSensor setDelay = 200000000
,D/LightsService(  731): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  731): LightSensor setSensorDelay = 200000000
D/Sensors (  731): Light sensor flush: not enabled 0
D/Sensors (  731): LightSensor enable = 1
D/Sensors (  731): LightSensor enableSensor = 1
D/SensorManager(  731): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
V/NetworkStats(  731): performPollLocked(flags=0x3)
,V/AlarmManager(  731): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,V/NetworkStats(  731): performPollLocked() took 150ms
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/Sensors (  731): LightSensor enable = 0
,D/Sensors (  731): LightSensor enableSensor = 0
,D/LightsService(  731): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  731): unregisterListener ::   
D/LightsService(  731): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  731): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  243): DCD ON
,I/ActivityManager(  731): Killing 4550:com.android.providers.calendar/u0a44 (adj 15): empty for 1800s
,I/ActivityManager(  731): Killing 4566:com.sec.android.app.voicenote/1000 (adj 15): empty for 1800s
,I/ActivityManager(  731): Killing 4543:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1800s
,I/ActivityManager(  731): Killing 4404:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty for 1803s
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 62
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 63
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  731): waitForAlarm result :8
,V/AlarmManager(  731): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  731): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  731): <AppSync3 Whitelist>
,V/AlarmManager(  731): (AppSync) com.google.android.gms : 900(900)
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager(  731): (AppSync) ### 1 added ###
D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,I/ActivityManager(  731): Killing 4470:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 3827:com.google.android.music:main/u0a122 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 4521:com.sec.phone/1001 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 4337:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 4131:com.android.calendar/u0a142 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 4562:com.sec.providers.settingsearch/u0a160 (adj 15): empty for 1851s
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  731): Killing 4724:com.wssyncmldm/1000 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 3868:com.sec.android.diagmonagent/1000 (adj 15): empty for 1851s
,I/ActivityManager(  731): Killing 4698:com.sec.knox.bridge/1000 (adj 15): empty for 1852s
,I/ActivityManager(  731): Killing 2979:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1852s
,I/ActivityManager(  731): Killing 4614:com.google.android.talk/u0a105 (adj 15): empty for 1852s
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/BatteryService(  731): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  731): !@Sync 64
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  731): stay LED for fully charged
,D/UiModeManager(  731): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1944): Disconnected process message: 10
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  243): DCD ON
D/SSRMv2:SIOP(  731): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  731): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
D/dalvikvm(  731): GC_CONCURRENT freed 3423K, 57% free 23492K/54456K, paused 23ms+39ms, total 422ms
I/PowerManagerService(  731): [PWL] Off : 1890s ago
D/AndroidRuntime( 5807): 
D/AndroidRuntime( 5807): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5807): CheckJNI is OFF
D/AndroidRuntime( 5807): setted country_code = Poland
D/AndroidRuntime( 5807): setted countryiso_code = PL
D/AndroidRuntime( 5807): setted sales_code = XEO
D/AndroidRuntime( 5807): readGMSProperty: start
D/AndroidRuntime( 5807): readGMSProperty: already setted!!
D/AndroidRuntime( 5807): readGMSProperty: end
D/AndroidRuntime( 5807): addProductProperty: start
D/dalvikvm( 5807): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5807): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5807): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5807): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5807): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/SMD     (  243): DCD ON
E/memtrack( 5807): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5807): failed to load memtrack module: -2
D/dalvikvm( 5807): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5807): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  731): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  731): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  731): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  731): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  731): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  731): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  731): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  731): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  731): getApplicationUninstallationEnabled
D/ApplicationPolicy(  731): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  731): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  731): START PACKAGE DELETE: observer{1146718640}
D/PackageManager(  731): pkg{<packageName>}
D/PackageManager(  731): user{0}
D/PackageManager(  731): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  731): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  731): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  731): Killing 5175:com.test.thalitest/u0a179 (adj 11): stop com.test.thalitest
I/ActivityManager(  731): Killing 5111:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1835s
I/ActivityManager(  731): Killing 3943:com.sec.spp.push/u0a38 (adj 15): empty for 1835s
I/ActivityManager(  731): Killing 5086:com.policydm/1000 (adj 15): empty for 1835s
I/ActivityManager(  731): Killing 4151:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1836s
I/ActivityManager(  731): Killing 5069:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1836s
I/ActivityManager(  731): Killing 5056:com.sec.pcw.device/1000 (adj 15): empty for 1836s
I/ActivityManager(  731): Killing 5041:com.android.musicfx/u0a24 (adj 15): empty for 1836s
I/ActivityManager(  731): Killing 5028:com.samsung.groupcast/u0a15 (adj 15): empty for 1836s
I/ActivityManager(  731): Killing 5010:com.google.android.partnersetup/u0a14 (adj 15): empty for 1836s
I/ActivityManager(  731): Killing 4998:com.sec.android.inputmethod/1000 (adj 15): empty for 1837s
I/ActivityManager(  731): Killing 4956:com.android.defcontainer/u0a6 (adj 15): empty for 1837s
W/PackageSettings(  731): Skipping PackageSetting{425b1e78 com.example.hello/10180} due to missing metadata
D/PackageManager(  731): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1085): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1066): action=android.intent.action.PACKAGE_REMOVED
D/PackageManager(  731): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/QuickConnect[1.1][2] ( 3277): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "sms"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5834): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5834):  
D/dalvikvm( 1403): GC_EXPLICIT freed 4278K, 46% free 10017K/18424K, paused 4ms+4ms, total 67ms
D/RCPManagerService(  731): PackageReceiver onReceive()
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
I/InputReader(  731): Reconfiguring input devices.  changes=0x00000010
I/SELinux ( 5834): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5834):  
I/SELinux ( 5834):  
I/SELinux ( 5834): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5834): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5834): >>>>> Normal User
E/dalvikvm( 5834): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5834): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "smsto"
I/HarmonyEASService(  731): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm( 2178): GC_EXPLICIT freed 530K, 41% free 10953K/18424K, paused 5ms+3ms, total 117ms
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "mms"
D/TimaKeyStoreProvider( 5834): in addTimaSignatureService
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5834): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5834): Added TimaKesytore provider
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "mmsto"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "sms"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5834, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "smsto"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "mms"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5834): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "mmsto"
D/elm:14132( 5834): ELMEngine.ELMEngine( context ).
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5834): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5834): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5834): ElmAgentService : onCreate()
D/elm:14132( 5834): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5834): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5834): MDMBridge.getInstance()
D/elm:14132( 5834): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5834): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 5850): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5850):  
D/BackupManagerService(  731): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/dalvikvm(  250): GC_EXPLICIT freed 43K, 49% free 9508K/18424K, paused 2ms+3ms, total 26ms
V/BackupManagerService(  731): removePackageParticipantsLocked: uid=10179 #1
D/EnterpriseDeviceManagerService(  731): Package has changed for user 0
D/EnterpriseDeviceManagerService(  731): Admin package name: com.google.android.gms
D/elm:14132( 5834): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18424K, paused 2ms+3ms, total 19ms
D/elm:14132( 5834): ElmAgentService : onDestroy().
I/ActivityManager(  731): Killing 3958:com.osp.app.signin/u0a43 (adj 15): empty for 1836s
I/SELinux ( 5850): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5850):  
I/SELinux ( 5850):  
I/SELinux ( 5850): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5850): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5850): >>>>> Normal User
E/dalvikvm( 5850): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 5850): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  731): GC_EXPLICIT freed 1745K, 57% free 23742K/54456K, paused 20ms+37ms, total 241ms
D/PackageManager(  731): delete sourFile : 
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 49% free 9508K/18424K, paused 2ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5850): in addTimaSignatureService
D/TimaKeyStoreProvider( 5850): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5850): Added TimaKesytore provider
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 5807): Shutting down VM
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  731): delete native library directory: 
D/PackageManager(  731): return delete result to caller: 1146718640
D/PackageManager(  731): returnCode: 1
D/dalvikvm( 5807): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "sms"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "smsto"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "mms"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  731):   Action: "android.intent.action.SENDTO"
I/PackageManager(  731):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  731):   Scheme: "mmsto"
I/PackageManager(  731): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=5850, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5850): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x427278e0, skipping init
I/SecureStorage( 5850): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 5850): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  329): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5850
I/SecureStorage(  329): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 5850): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 5850): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  329): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5850
I/SecureStorage(  329): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  731): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  731): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  731): clearDefaults: com.test.thalitest
D/InputReader(  731): Processing first event
W/ApplicationsProvider( 1403): Could not fetch usage stats
W/ApplicationsProvider( 1403): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1403): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1403): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1403): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1403): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1403): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
