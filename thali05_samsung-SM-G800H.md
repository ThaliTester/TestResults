#### Test 5065027865f659b_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5206): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5206):  
--------- beginning of /dev/log/system
I/ActivityManager(  729): Killing 3920:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,D/dalvikvm(  252): GC_EXPLICIT freed 46K, 50% free 9506K/19000K, paused 2ms+3ms, total 29ms
I/SELinux ( 5206): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5206):  
I/SELinux ( 5206):  
I/SELinux ( 5206): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm(  252): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 2ms+3ms, total 18ms
E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5206): >>>>> Normal User
E/dalvikvm( 5206): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5206): in addTimaSignatureService
D/dalvikvm(  252): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 2ms+2ms, total 19ms
D/TimaKeyStoreProvider( 5206): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5206): Added TimaKesytore provider
V/AlarmManager(  729): waitForAlarm result :4
V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
D/BatteryService(  729): stay LED for fully charged
D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5206, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
E/SMD     (  243): DCD ON
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5206): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/cutils  (  230): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5206): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  729): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  230): Returning OperationFailed - no handler for errno 30
D/AndroidRuntime( 5218): 
D/AndroidRuntime( 5218): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5218): CheckJNI is OFF
D/AndroidRuntime( 5218): setted country_code = Poland
D/AndroidRuntime( 5218): setted countryiso_code = PL
D/AndroidRuntime( 5218): setted sales_code = XEO
D/AndroidRuntime( 5218): readGMSProperty: start
D/AndroidRuntime( 5218): readGMSProperty: already setted!!
D/AndroidRuntime( 5218): readGMSProperty: end
D/AndroidRuntime( 5218): addProductProperty: start
D/dalvikvm( 5218): Trying to load lib libjavacore.so 0x0
I/SA      ( 3990): [PMR] Received action : android.intent.action.PACKAGE_ADDED
D/dalvikvm( 5218): Added shared lib libjavacore.so 0x0
I/SA      ( 3990): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
D/dalvikvm( 5218): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5218): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5218): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SA      ( 3990): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4284): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2174): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5243): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5243):  
E/memtrack( 5218): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5218): failed to load memtrack module: -2
I/SELinux ( 5243): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5243):  
I/SELinux ( 5243):  
I/SELinux ( 5243): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5243): >>>>> Normal User
E/dalvikvm( 5243): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5243): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/ActivityManager(  729): Killing 3933:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/dalvikvm( 5218): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 2174): GC_CONCURRENT freed 6484K, 42% free 11203K/19000K, paused 4ms+3ms, total 106ms
D/dalvikvm( 2174): WAIT_FOR_CONCURRENT_GC blocked 50ms
D/TimaKeyStoreProvider( 5243): in addTimaSignatureService
D/TimaKeyStoreProvider( 5243): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5243): Added TimaKesytore provider
D/AndroidRuntime( 5218): Calling main entry com.android.commands.am.Am
I/IcingCorporaProvider( 2174): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5243, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 5243): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 5259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5259):  
I/ActivityManager(  729): Killing 4213:com.sec.android.service.health/u0a16 (adj 15): empty #43
V/ApplicationPolicy(  729): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SELinux ( 5259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5259):  
I/SELinux ( 5259):  
I/SELinux ( 5259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5259): >>>>> Normal User
E/dalvikvm( 5259): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5259): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.acquire()
D/TimaKeyStoreProvider( 5259): in addTimaSignatureService
D/TimaKeyStoreProvider( 5259): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5259): Added TimaKesytore provider
I/SELinux ( 5271): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5271):  
D/LockPatternUtils( 1067): isPcwEnable = null
D/AndroidRuntime( 5218): Shutting down VM
D/dalvikvm( 5218): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
D/SurfaceWidgetView( 1260): destroyHardwareResources():1126398264
I/SurfaceFlinger(  250): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  250): id=13 Removed CatteryCove (-2/12)
I/SELinux ( 5271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5271):  
I/SELinux ( 5271):  
I/SELinux ( 5271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
E/dalvikvm( 5271): >>>>> Normal User
E/dalvikvm( 5271): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SurfaceFlinger(  250): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  250): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5271): in addTimaSignatureService
D/TimaKeyStoreProvider( 5271): Cannot add TimaSignature Service, License check Failed
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/ActivityThread( 5271): Added TimaKesytore provider
D/Launcher( 1260): onTrimMemory. Level: 20
D/LockPatternUtils( 1067): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2099): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2099): getDatabaseLocked(b,b,pwd)...
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5271, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5271, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5271): Binding Chromium to the background looper Looper (main, tid 1) {423082b0}
I/chromium( 5271): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5271): Initializing chromium process, renderers=0
W/chromium( 5271): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5271): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5271): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5271): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5271): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5271): Remote Branch: 
I/Adreno-EGL( 5271): Local Patches: 
I/Adreno-EGL( 5271): Reconstruct Branch: 
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5259, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/dalvikvm( 5271): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5271): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5271): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5271): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5271): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5271): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5271): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5271): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5271): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5271): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5271): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5271): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5271): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5271): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5271): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5271): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5271): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5271): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5271): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  250): id=16 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5271): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5271): Enabling debug mode 0
W/AwContents( 5271): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5315): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5315):  
I/ActivityManager(  729): Killing 3946:com.sec.android.soagent/u0a37 (adj 15): empty #43
W/GAV2    ( 5259): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5315): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5315):  
I/SELinux ( 5315):  
I/SELinux ( 5315): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5315): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5315): >>>>> Normal User
E/dalvikvm( 5315): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5315): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5315): in addTimaSignatureService
D/TimaKeyStoreProvider( 5315): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5315): Added TimaKesytore provider
D/PackageIntentReceiver( 5315): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5315): Not GearManger package! 
D/JsMessageQueue( 5271): Set native->JS mode to OnlineEventsBridgeMode
I/SELinux ( 5334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5334):  
I/SELinux ( 5334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5334):  
I/SELinux ( 5334):  
I/SELinux ( 5334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5334): >>>>> Normal User
E/dalvikvm( 5334): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5334): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5334): in addTimaSignatureService
D/TimaKeyStoreProvider( 5334): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5334): Added TimaKesytore provider
D/dalvikvm( 5271): Trying to load lib /data/app-lib/com.test.thalitest-18/libjxcore.so 0x4262f020
D/MagazineService Version( 5334): Magazine-Channel: 13
D/MagazineService Version( 5334): Magazine-Provider: 13
D/MagazineService Version( 5334): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5334): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5334): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5334, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 5271): Added shared lib /data/app-lib/com.test.thalitest-18/libjxcore.so 0x4262f020
D/jxcore_app_log( 5271): JniHelper::setJavaVM(0x417754f8), pthread_self() = 2025208816
D/JX-Cordova( 5271): jxcore cordova android initializing
I/MagazineService::MagazineService( 5334): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/dalvikvm( 5271): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5271): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5271): VFY: replacing opcode 0x6e at 0x0045
I/SELinux ( 5347): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5347):  
D/MagazineService::MagazineService( 5334): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  729): Killing 1344:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5347): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5347):  
I/SELinux ( 5347):  
I/SELinux ( 5347): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5347): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5347): >>>>> Normal User
E/dalvikvm( 5347): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5347): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/GAV2    ( 5259): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/TimaKeyStoreProvider( 5347): in addTimaSignatureService
D/TimaKeyStoreProvider( 5347): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5347): Added TimaKesytore provider
I/ActivityManager(  729): Killing 4324:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
I/SELinux ( 5361): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5361):  
I/ActivityManager(  729): Killing 4339:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5361): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5361):  
I/SELinux ( 5361):  
,I/SELinux ( 5361): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5361): >>>>> Normal User
,E/dalvikvm( 5361): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5361): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5361): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5361): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5361): Added TimaKesytore provider
,D/dalvikvm( 5271): GC_CONCURRENT freed 4925K, 33% free 12762K/19000K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 5271): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 5271): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5361, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5361): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5373): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5373):  
,I/ActivityManager(  729): Killing 4351:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5373):  
I/SELinux ( 5373):  
,I/SELinux ( 5373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5373): >>>>> Normal User
,E/dalvikvm( 5373): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5373): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5373): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5373): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5373): Added TimaKesytore provider
,I/ActivityManager(  729): Killing 3531:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/PackageBroadcastService( 1747): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1747): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1747): Module APK com.google.android.play.games already loaded
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@9
,I/PowerManagerService(  729): [PWL] Off : 50s ago
I/PowerManagerService(  729): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  729): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  729): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=729, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=2175)
,D/dalvikvm( 1747): GC_CONCURRENT freed 1923K, 38% free 11795K/19000K, paused 6ms+4ms, total 93ms
,W/SQLiteConnectionPool( 1747): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 1747): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1747): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1747): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1747): Submit a task: h
,D/ChimeraCfgMgr( 1747): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1747): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1747): Processing package: com.test.thalitest
,W/BaseAppContext( 1747): Using Auth Proxy for data requests.
,W/BaseAppContext( 1747): Using Auth Proxy for data requests.
,D/Finsky  ( 3686): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/GassUtils( 1747): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/h       ( 1747): Found info for package com.test.thalitest in db.
,I/PeopleContactsSync( 1747): CP2 sync disabled
,I/dalvikvm( 1747): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
,W/dalvikvm( 1747): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1747): VFY: replacing opcode 0x6e at 0x000e
,W/BaseAppContext( 1747): Using Auth Proxy for data requests.
,W/BaseAppContext( 1747): Using Auth Proxy for data requests.
,W/BaseAppContext( 1747): Using Auth Proxy for data requests.
,W/BaseAppContext( 1747): Using Auth Proxy for data requests.
,D/dalvikvm( 5271): GC_FOR_ALLOC freed 4701K, 28% free 15765K/21800K, paused 33ms, total 39ms
,D/dalvikvm( 5271): GC_FOR_ALLOC freed 5047K, 32% free 16771K/24472K, paused 36ms, total 39ms
,I/dalvikvm-heap( 5271): Grow heap (frag case) to 22.003MB for 2459024-byte allocation
,D/SSRMv2:SIOP(  729): SIOP:: AP = 320, Delta = 10
,E/SMD     (  243): DCD ON
,D/dalvikvm( 5271): GC_FOR_ALLOC freed 3768K, 36% free 17452K/26876K, paused 31ms, total 33ms
,D/dalvikvm( 5271): GC_FOR_ALLOC freed 1223K, 36% free 17357K/26876K, paused 28ms, total 30ms
,W/jxcore-log( 5271): Initializing JXcore engine
,W/jxcore-log( 5271): JXcore engine is ready
,W/jxcore-log( 5271): Starting JXcore engine
,W/jxcore-log( 5271): Platform android
W/jxcore-log( 5271): 
,W/jxcore-log( 5271): Process ARCH arm
W/jxcore-log( 5271): 
,I/jxcore-log( 5271): JXcore Cordova bridge is ready!
I/jxcore-log( 5271): 
,W/jxcore-log( 5271): JXcore engine is started
,I/chromium( 5271): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5271): Error!: missing ) after argument list
E/jxcore  ( 5271): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5271): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1067): isPcwEnable = null
I/ActivityManager(  729): Killing 4379:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
,I/SurfaceFlinger(  250): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  250): id=16 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  729): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/SurfaceWidgetView( 1260): destroyHardwareResources():1126398264
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1260): onRestart, Launcher: 1114462664
D/Launcher( 1260): onStart, Launcher: 1114462664
,D/Launcher.HomeView( 1260): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1449): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  250): id=17 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  250): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1260): onStop
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  729): mDVFSHelper.release()
,D/AmoledAdjustTimer(  729): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  243): DCD ON
,I/GAV2    ( 5259): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4048): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4048): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4048): Breath 67230 latestRequest time : 1449598347546 current time : 1449598414777
,I/VacuumService( 1296): Vacuum at: now=1449598414926 tag=VacuumService
,D/UdcCache:FPQuery( 1747): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1296): GC_EXPLICIT freed 1489K, 42% free 11138K/19000K, paused 5ms+5ms, total 49ms
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  243): DCD ON
,D/FactoryTest( 4691): Not factory mode
,D/FactoryTest( 4691): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4691): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4691): still no open session command from host, so toast
W/ContextImpl( 4691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,D/dalvikvm(  729): GC_EXPLICIT freed 2567K, 58% free 23632K/55704K, paused 7ms+13ms, total 133ms
,V/ApplicationPolicy(  729): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  729): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 2099): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2099): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/LockPatternUtils( 1067): isPcwEnable = null
,E/MTPRx   ( 4691): started activity for popup
,D/GetConfigurationSnapshotOperation( 1296): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/SettingsReceiverActivity( 4691): PREF_DONT_ASK_AGAIN : false
,D/SettingsReceiverActivity( 4691): dev.kiessupport is : TRUE
,I/PhenotypeFlagCommitter( 1296): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1296): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1296): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 1296): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x0033
,I/SurfaceFlinger(  250): id=19 createSurf (1x1),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 4691): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4691): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4691): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4691): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4691): Remote Branch: 
I/Adreno-EGL( 4691): Local Patches: 
I/Adreno-EGL( 4691): Reconstruct Branch: 
I/System.out( 1296): Thread-118(HTTPLog):isShipBuild true
,I/System.out( 1296): Thread-118(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/HWUI    ( 4691): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4691): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  729): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  729): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/GetCommittedConfigurationOperation( 1296): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1296):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1296): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1296): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1296): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/CustomFrequencyManagerService(  729): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 729  tag : ACTIVITY_RESUME_BOOSTER@9
D/dalvikvm( 1296): GC_CONCURRENT freed 1665K, 41% free 11392K/19000K, paused 4ms+4ms, total 28ms
,I/HarmonyEASService(  729): Updating for all 1
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 320, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3686): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3686): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = -20
,E/Watchdog(  729): !@Sync 4
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 295, currTemp = 297, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 75s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4048): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4048): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4048): Breath 90038 latestRequest time : 1449598347546 current time : 1449598437584
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  729): !@Sync 5
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 294, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 105s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,D/Headlines( 4048): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4048): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4048): Breath 120039 latestRequest time : 1449598347546 current time : 1449598467588
,D/Headlines( 4048): stop 
,D/Headlines( 4048): Breath.onDestroy : 
,I/ActivityManager(  729): Killing 4395:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  729): !@Sync 6
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 140s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  729): !@Sync 7
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 180s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  729): !@Sync 8
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  243): DCD ON
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  729): stay LED for fully charged
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 9
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 225s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  729): initializing...
,I/TLC_TIMA_PKM_initialize(  729): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  729): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  729): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  729): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  729): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  729): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  729): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  729): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  729): App is not loaded in QSEE
,D/QSEECOMAPI: (  729): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  729): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  729): Trustlet response is completed
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  729): !@Sync 10
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager(  729): waitForAlarm result :4
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5503): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5503):  
,I/PowerManagerService(  729): [PWL] Off : 275s ago
,I/PowerManagerService(  729): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  729): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  729): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=729, ws=WorkSource{10075}) (elapsedTime=156)
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5503): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5503):  
I/SELinux ( 5503):  
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,I/SELinux ( 5503): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5503): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5503): >>>>> Normal User
,E/dalvikvm( 5503): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5503): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5503): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5503): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5503): Added TimaKesytore provider
,W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5503, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  729): Killing 4420:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 11
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 12
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  729): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 330s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 13
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 14
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 390s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 15
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/dalvikvm(  729): GC_CONCURRENT freed 3616K, 58% free 23453K/55704K, paused 21ms+39ms, total 425ms
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 16
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 455s ago
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 17
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 18
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 19
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 525s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  729): !@Sync 20
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  729): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 21
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 600s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 22
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  729): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  729): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
V/AlarmManager(  729): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 23
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 24
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 680s ago
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 25
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 26
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 27
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 765s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 28
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 29
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  729): !@Sync 30
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  729): [PWL] Off : 855s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm(  729): GC_CONCURRENT freed 3372K, 58% free 23480K/55152K, paused 22ms+38ms, total 420ms
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 31
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :4
,I/SensorManagerA(  729): getReportingMode :: sensor.mType = 5
D/LightsService(  729): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Sensors (  729): LightSensor setDelay = 200000000
,D/Sensors (  729): LightSensor setSensorDelay = 200000000
,D/Sensors (  729): Light sensor flush: not enabled 0
D/Sensors (  729): LightSensor enable = 1
,D/Sensors (  729): LightSensor enableSensor = 1
,D/SensorManager(  729): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  729): LightSensor enable = 0
,D/Sensors (  729): LightSensor enableSensor = 0
,D/SensorManager(  729): unregisterListener ::   
D/LightsService(  729): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  729): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  243): DCD ON
,D/ConnectivityService(  729): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  729): !@Sync 32
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 33
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 950s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 34
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 35
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 36
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
E/SMD     (  243): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1050s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 37
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 38
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 39
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 40
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 41
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 42
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  729): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  729): <AppSync3 Whitelist>
,V/AlarmManager(  729): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 43
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 44
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 45
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 46
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/dalvikvm(  729): GC_CONCURRENT freed 3392K, 58% free 23493K/55152K, paused 24ms+38ms, total 415ms
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 47
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1380s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 48
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 49
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  243): DCD ON
D/UiModeManager(  729): mCoverManager.getCoverState() : true
D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 50
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 51
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1500s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 52
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 53
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 54
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-16, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  729): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 55
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1625s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 56
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 57
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  729): stay LED for fully charged
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 58
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 59
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/TimaService(  729): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  729): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  729): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/BatteryService(  729): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  729): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  729): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 60
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  729): [PWL] Off : 1755s ago
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  729): Prepared write state in 115ms
,I/ProcessStatsService(  729): Prepared write state in 89ms
,E/SMD     (  243): DCD ON
,I/ProcessStatsService(  729): Pruning old procstats: /data/system/procstats/state-2015-12-08-04-13-46.bin
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/dalvikvm(  729): GC_CONCURRENT freed 3393K, 58% free 23528K/54932K, paused 20ms+38ms, total 419ms
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 61
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :4
,D/LightsService(  729): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  729): getReportingMode :: sensor.mType = 5
D/Sensors (  729): LightSensor setDelay = 200000000
D/Sensors (  729): LightSensor setSensorDelay = 200000000
D/Sensors (  729): Light sensor flush: not enabled 0
D/Sensors (  729): LightSensor enable = 1
D/Sensors (  729): LightSensor enableSensor = 1
D/SensorManager(  729): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked(flags=0x3)
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  729): stay LED for fully charged
,V/AlarmManager(  729): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Sensors (  729): LightSensor enable = 0
,D/Sensors (  729): LightSensor enableSensor = 0
D/LightsService(  729): [SvcLED]  onSensorChanged::light value = 0
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/SensorManager(  729): unregisterListener ::   
D/LightsService(  729): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
V/NetworkStats(  729): performPollLocked() took 217ms
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,D/NtpTrustedTime(  729): currentTimeMillis() cache hit
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  243): DCD ON
,I/EventLogService( 1747): Aggregate from 1449598341335 (log), 1449598341335 (data)
,D/ConnectivityService(  729): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  243): DCD ON
,I/ActivityManager(  729): Killing 2996:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4639:com.google.android.talk/u0a105 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4583:com.android.providers.calendar/u0a44 (adj 15): empty for 1801s
,I/ActivityManager(  729): Killing 4577:com.sec.android.app.voicenote/1000 (adj 15): empty for 1801s
,I/ActivityManager(  729): Killing 4556:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1801s
,I/ActivityManager(  729): Killing 4439:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty for 1803s
,I/ActivityManager(  729): Killing 4722:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4748:com.wssyncmldm/1000 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 3904:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4367:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4159:com.android.calendar/u0a142 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4597:com.sec.providers.settingsearch/u0a160 (adj 15): empty for 1800s
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4,
,I/ActivityManager(  729): Killing 4536:com.sec.phone/1001 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 4503:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1800s
,I/ActivityManager(  729): Killing 3852:com.google.android.music:main/u0a122 (adj 15): empty for 1800s
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 62
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  729): waitForAlarm result :8
,V/AlarmManager(  729): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  729): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  729): <AppSync3 Whitelist>
,V/AlarmManager(  729): (AppSync) com.google.android.gms : 900(900)
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager(  729): (AppSync) ### 1 added ###
D/KeyguardUpdateMonitor( 1067): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/Watchdog(  729): !@Sync 63
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1933): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  729): mCoverManager.getCoverState() : true
,D/BatteryService(  729): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
,V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  729): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  729): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  243): DCD ON
E/Watchdog(  729): !@Sync 64
D/BatteryService(  729): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
D/BatteryService(  729): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  729): mCoverManager.getCoverState() : true
D/BatteryService(  729): stay LED for fully charged
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
V/HeadsetService( 1933): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 1933): Disconnected process message: 10
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  243): DCD ON
D/AndroidRuntime( 5903): 
D/AndroidRuntime( 5903): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5903): CheckJNI is OFF
D/AndroidRuntime( 5903): setted country_code = Poland
D/AndroidRuntime( 5903): setted countryiso_code = PL
D/AndroidRuntime( 5903): setted sales_code = XEO
D/AndroidRuntime( 5903): readGMSProperty: start
D/AndroidRuntime( 5903): readGMSProperty: already setted!!
D/AndroidRuntime( 5903): readGMSProperty: end
D/AndroidRuntime( 5903): addProductProperty: start
D/dalvikvm( 5903): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5903): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5903): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5903): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5903): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5903): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5903): failed to load memtrack module: -2
D/dalvikvm( 5903): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5903): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  729): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  729): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  729): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  729): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  729): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  729): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  729): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  729): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  729): getApplicationUninstallationEnabled
D/ApplicationPolicy(  729): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  729): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  729): START PACKAGE DELETE: observer{1122068016}
D/PackageManager(  729): pkg{<packageName>}
D/PackageManager(  729): user{0}
D/PackageManager(  729): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  729): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  729): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  729): Killing 5271:com.test.thalitest/u0a179 (adj 11): stop com.test.thalitest
I/ActivityManager(  729): Killing 5206:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1827s
I/ActivityManager(  729): Killing 3976:com.sec.spp.push/u0a38 (adj 15): empty for 1828s
I/ActivityManager(  729): Killing 5185:com.policydm/1000 (adj 15): empty for 1828s
I/ActivityManager(  729): Killing 4188:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1828s
I/ActivityManager(  729): Killing 5163:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1828s
I/ActivityManager(  729): Killing 5142:com.sec.pcw.device/1000 (adj 15): empty for 1828s
I/ActivityManager(  729): Killing 5125:com.android.musicfx/u0a24 (adj 15): empty for 1829s
I/ActivityManager(  729): Killing 5113:com.samsung.groupcast/u0a15 (adj 15): empty for 1829s
I/ActivityManager(  729): Killing 5098:com.google.android.partnersetup/u0a14 (adj 15): empty for 1829s
I/ActivityManager(  729): Killing 5086:com.sec.android.inputmethod/1000 (adj 15): empty for 1829s
I/ActivityManager(  729): Killing 5019:com.android.defcontainer/u0a6 (adj 15): empty for 1830s
W/PackageSettings(  729): Skipping PackageSetting{42aeb1a0 com.example.hello/10180} due to missing metadata
E/SMD     (  243): DCD ON
D/PackageManager(  729): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  729): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1067): action=android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2174): GC_EXPLICIT freed 530K, 43% free 10952K/19000K, paused 6ms+5ms, total 51ms
D/QuickConnect[1.1][2] ( 3307): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader(  729): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1210): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Scheme: "sms"
D/dalvikvm( 1398): GC_EXPLICIT freed 4277K, 48% free 10016K/19000K, paused 4ms+9ms, total 81ms
I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
I/SELinux ( 5929): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5929):  
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mmsto"
I/SELinux ( 5929): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5929):  
I/SELinux ( 5929):  
I/SELinux ( 5929): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5929): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5929): >>>>> Normal User
E/dalvikvm( 5929): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5929): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5929): in addTimaSignatureService
D/TimaKeyStoreProvider( 5929): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5929): Added TimaKesytore provider
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  729): GC_EXPLICIT freed 2362K, 58% free 23620K/54932K, paused 9ms+21ms, total 270ms
D/dalvikvm(  729): WAIT_FOR_CONCURRENT_GC blocked 245ms
D/EnterpriseDeviceManagerService(  729): Package has changed for user 0
D/EnterpriseDeviceManagerService(  729): Admin package name: com.google.android.gms
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  729): PackageReceiver onReceive()
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5929, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mmsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  729): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 5929): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5929): ELMEngine.ELMEngine( context ).
D/elm:14132( 5929): MDMBridge.setEnterpriseBridge()
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 5929): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5929): ElmAgentService : onCreate()
I/SELinux ( 5945): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5945):  
D/elm:14132( 5929): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5929): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5929): MDMBridge.getInstance()
D/elm:14132( 5929): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5929): MDMBridge.getAllLicenseInfoFromSDK()
D/dalvikvm(  252): GC_EXPLICIT freed 44K, 50% free 9506K/19000K, paused 4ms+4ms, total 41ms
D/dalvikvm(  252): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 2ms+4ms, total 28ms
I/SELinux ( 5945): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5945):  
I/SELinux ( 5945):  
I/SELinux ( 5945): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5945): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5945): >>>>> Normal User
E/dalvikvm( 5945): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
D/elm:14132( 5929): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
E/SELinux ( 5945): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  252): GC_EXPLICIT freed <1K, 50% free 9506K/19000K, paused 3ms+5ms, total 31ms
D/elm:14132( 5929): ElmAgentService : onDestroy().
I/ActivityManager(  729): Killing 3990:com.osp.app.signin/u0a43 (adj 15): empty for 1828s
D/TimaKeyStoreProvider( 5945): in addTimaSignatureService
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 5945): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5945): Added TimaKesytore provider
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  729): GC_EXPLICIT freed 813K, 58% free 23541K/54932K, paused 15ms+33ms, total 353ms
D/PackageManager(  729): delete sourFile : 
D/PackageManager(  729): delete native library directory: 
D/PackageManager(  729): return delete result to caller: 1122068016
D/AndroidRuntime( 5903): Shutting down VM
D/dalvikvm( 5903): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 4ms
D/PackageManager(  729): returnCode: 1
D/BackupManagerService(  729): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  729): removePackageParticipantsLocked: uid=10179 #1
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "sms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "smsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mms"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  729): Permission Denial: getCurrentUser() from pid=5945, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  729):   Action: "android.intent.action.SENDTO"
I/PackageManager(  729):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  729):   Scheme: "mmsto"
I/PackageManager(  729): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 5945): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42637d60, skipping init
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 5945): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 5945): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  302): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5945
I/SecureStorage(  302): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 5945): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 5945): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  302): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5945
I/SecureStorage(  302): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  729): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  729): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  729): clearDefaults: com.test.thalitest
W/ApplicationsProvider( 1398): Could not fetch usage stats
W/ApplicationsProvider( 1398): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1398): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1398): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1398): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1398): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1398): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1398): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1398): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1398): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1398): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1398): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/InputReader(  729): Processing first event

```
