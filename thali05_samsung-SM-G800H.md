#### Test 50650278352fc1f_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 5172): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5172):  
--------- beginning of /dev/log/system
I/ActivityManager(  735): Killing 3942:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  248): GC_EXPLICIT freed 46K, 49% free 9509K/18464K, paused 2ms+3ms, total 33ms
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9509K/18464K, paused 2ms+3ms, total 19ms
I/SELinux ( 5172): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5172):  
I/SELinux ( 5172):  
I/SELinux ( 5172): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5172): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5172): >>>>> Normal User
E/dalvikvm( 5172): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
E/SELinux ( 5172): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9509K/18464K, paused 1ms+9ms, total 25ms
D/TimaKeyStoreProvider( 5172): in addTimaSignatureService
D/TimaKeyStoreProvider( 5172): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5172): Added TimaKesytore provider
,V/AlarmManager(  735): waitForAlarm result :4
D/SSRMv2:SIOP(  735): SIOP:: AP = 310, Delta = 0
V/AlarmManager(  735): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  735): stay LED for fully charged
D/UiModeManager(  735): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5172, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5172): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5172): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/ActivityManager(  735): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/SA      ( 4025): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4025): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4025): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 4324): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2188): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
D/AndroidRuntime( 5191): 
D/AndroidRuntime( 5191): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5191): CheckJNI is OFF
D/AndroidRuntime( 5191): setted country_code = Poland
D/AndroidRuntime( 5191): setted countryiso_code = PL
D/AndroidRuntime( 5191): setted sales_code = XEO
D/AndroidRuntime( 5191): readGMSProperty: start
D/AndroidRuntime( 5191): readGMSProperty: already setted!!
D/AndroidRuntime( 5191): readGMSProperty: end
D/AndroidRuntime( 5191): addProductProperty: start
I/SELinux ( 5208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5208):  
D/dalvikvm( 5191): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5191): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5191): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5191): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5191): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5208):  
I/SELinux ( 5208):  
I/SELinux ( 5208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5208): >>>>> Normal User
E/dalvikvm( 5208): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 5208): in addTimaSignatureService
D/TimaKeyStoreProvider( 5208): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5208): Added TimaKesytore provider
I/IcingCorporaProvider( 2188): UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
I/ActivityManager(  735): Killing 3955:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/CapabilityManagerService New( 5208): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5208, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/FactoryTest( 4740): Not factory mode
D/FactoryTest( 4740): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4740): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4740): still no open session command from host, so toast
W/ContextImpl( 4740): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4740): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
I/SELinux ( 5229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5229):  
V/ApplicationPolicy(  735): isApplicationStateBlocked userId 0 pkgname com.android.settings
I/ActivityManager(  735): Killing 4236:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/CustomFrequencyManagerService(  735): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  pkgName : ACTIVITY_RESUME_BOOSTER@5
E/memtrack( 5191): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5191): failed to load memtrack module: -2
W/ActivityManager(  735): mDVFSHelper.acquire()
D/LockPatternUtils( 1065): isPcwEnable = null
I/SELinux ( 5229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5229):  
I/SELinux ( 5229):  
I/SELinux ( 5229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5229): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5229): >>>>> Normal User
E/dalvikvm( 5229): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
D/LockPatternUtils( 1065): isPcwEnable = null
E/SELinux ( 5229): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/MTPRx   ( 4740): started activity for popup
D/dalvikvm( 5191): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/SQLiteSecureOpenHelper( 2108): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2108): getDatabaseLocked(b,b,pwd)...
E/SettingsReceiverActivity( 4740): PREF_DONT_ASK_AGAIN : false
D/TimaKeyStoreProvider( 5229): in addTimaSignatureService
D/TimaKeyStoreProvider( 5229): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5229): Added TimaKesytore provider
D/AndroidRuntime( 5191): Calling main entry com.android.commands.am.Am
D/SettingsReceiverActivity( 4740): dev.kiessupport is : TRUE
V/ApplicationPolicy(  735): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  735): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  tag : ACTIVITY_RESUME_BOOSTER@5
D/CustomFrequencyManagerService(  735): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  735): mDVFSHelper.acquire()
I/SELinux ( 5248): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5248):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 5191): Shutting down VM
I/SurfaceFlinger(  246): id=16 createSurf (1x1),1 flag=4, TettingsRec
D/dalvikvm( 5191): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/Adreno-EGL( 4740): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4740): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4740): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4740): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4740): Remote Branch: 
I/Adreno-EGL( 4740): Local Patches: 
I/Adreno-EGL( 4740): Reconstruct Branch: 
I/SELinux ( 5248): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5248):  
I/SELinux ( 5248):  
I/SELinux ( 5248): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5248): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5248): >>>>> Normal User
E/dalvikvm( 5248): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
I/HWUI    ( 4740): EGLImpl-HWUI Protected EGL context created
E/SELinux ( 5248): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5248): in addTimaSignatureService
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5229, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 5248): Cannot add TimaSignature Service, License check Failed
D/OpenGLRenderer( 4740): Enabling debug mode 0
D/ActivityThread( 5248): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtils( 1065): isPcwEnable = null
D/SurfaceWidgetView( 1251): destroyHardwareResources():1125914800
I/SQLiteSecureOpenHelper( 2108): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2108): getDatabaseLocked(b,b,pwd)...
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5248, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5248, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (8/13)
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (-2/13)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (7/12)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (-2/12)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
V/WebViewChromium( 5248): Binding Chromium to the background looper Looper (main, tid 1) {42292308}
D/Launcher( 1251): onTrimMemory. Level: 20
I/chromium( 5248): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5248): Initializing chromium process, renderers=0
W/chromium( 5248): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/Adreno-EGL( 5248): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5248): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5248): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5248): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5248): Remote Branch: 
I/Adreno-EGL( 5248): Local Patches: 
I/Adreno-EGL( 5248): Reconstruct Branch: 
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=16 Removed TettingsRec (7/11)
I/SurfaceFlinger(  246): id=16 Removed TettingsRec (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/dalvikvm( 5248): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5248): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5248): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5248): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5248): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5248): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 5248): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5248): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5248): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5248): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5248): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5248): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5248): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5248): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5248): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5248): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5248): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5248): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5248): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger(  246): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5248): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5248): Enabling debug mode 0
W/AwContents( 5248): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  735): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  735): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  735): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  pkgName : ACTIVITY_RESUME_BOOSTER@9
W/GAV2    ( 5229): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 5297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5297):  
I/SELinux ( 5297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5297):  
I/SELinux ( 5297):  
I/SELinux ( 5297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5297): >>>>> Normal User
E/dalvikvm( 5297): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 5297): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5297): in addTimaSignatureService
D/TimaKeyStoreProvider( 5297): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5297): Added TimaKesytore provider
D/PackageIntentReceiver( 5297): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5297): Not GearManger package! 
I/SELinux ( 5312): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5312):  
I/ActivityManager(  735): Killing 3968:com.sec.android.soagent/u0a37 (adj 15): empty #43
I/SELinux ( 5312): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5312):  
I/SELinux ( 5312):  
I/SELinux ( 5312): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5312): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5312): >>>>> Normal User
E/dalvikvm( 5312): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 5312): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5312): in addTimaSignatureService
D/TimaKeyStoreProvider( 5312): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5312): Added TimaKesytore provider
D/JsMessageQueue( 5248): Set native->JS mode to OnlineEventsBridgeMode
D/MagazineService Version( 5312): Magazine-Channel: 13
D/MagazineService Version( 5312): Magazine-Provider: 13
D/MagazineService Version( 5312): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 5312): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 5312): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5312, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 5312): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 5328): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5328):  
D/MagazineService::MagazineService( 5312): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  735): Killing 1340:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 5328): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5328):  
I/SELinux ( 5328):  
I/SELinux ( 5328): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5328): >>>>> Normal User
E/dalvikvm( 5328): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 5328): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5328): in addTimaSignatureService
D/TimaKeyStoreProvider( 5328): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5328): Added TimaKesytore provider
D/dalvikvm( 5248): Trying to load lib /data/app-lib/com.test.thalitest-14/libjxcore.so 0x425b9078
W/GAV2    ( 5229): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  735): Killing 4364:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
D/dalvikvm( 5248): Added shared lib /data/app-lib/com.test.thalitest-14/libjxcore.so 0x425b9078
D/jxcore_app_log( 5248): JniHelper::setJavaVM(0x4177a528), pthread_self() = 2033296664
D/JX-Cordova( 5248): jxcore cordova android initializing
I/dalvikvm( 5248): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5248): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5248): VFY: replacing opcode 0x6e at 0x0045
,I/SELinux ( 5342): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5342):  
I/ActivityManager(  735): Killing 4380:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
,I/SELinux ( 5342): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5342):  
I/SELinux ( 5342):  
,I/SELinux ( 5342): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5342): >>>>> Normal User
,E/dalvikvm( 5342): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5342): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5342): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5342): Added TimaKesytore provider
,W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5342, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5342): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5354): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5354):  
I/ActivityManager(  735): Killing 4392:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,D/dalvikvm( 5248): GC_CONCURRENT freed 4924K, 31% free 12765K/18464K, paused 1ms+2ms, total 36ms
,D/dalvikvm( 5248): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 5248): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SELinux ( 5354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5354):  
I/SELinux ( 5354):  
,I/SELinux ( 5354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5354): >>>>> Normal User
,E/dalvikvm( 5354): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5354): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5354): in addTimaSignatureService
D/TimaKeyStoreProvider( 5354): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5354): Added TimaKesytore provider
,I/ActivityManager(  735): Killing 3556:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/PackageBroadcastService( 1784): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
,E/SMD     (  240): DCD ON
,D/CustomFrequencyManagerService(  735): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  tag : ACTIVITY_RESUME_BOOSTER@9
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleContactsSync( 1784): CP2 sync disabled
,D/AsyncTaskServiceImpl( 1784): Submit a task: h
,I/dalvikvm( 1784): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1784): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x000e
,D/dalvikvm( 1784): GC_CONCURRENT freed 1911K, 36% free 11864K/18464K, paused 8ms+11ms, total 134ms
,D/dalvikvm( 1784): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 1784): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/SQLiteConnectionPool( 1784): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,D/h       ( 1784): Processing package: com.test.thalitest
,D/Headlines( 4078): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Finsky  ( 3707): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Headlines( 4078): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4078): Breath 70148 latestRequest time : 1449588488423 current time : 1449588558571
,D/GassUtils( 1784): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/h       ( 1784): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,D/dalvikvm( 5248): GC_FOR_ALLOC freed 4697K, 26% free 15767K/21260K, paused 35ms, total 36ms
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,I/VacuumService( 1297): Vacuum at: now=1449588558786 tag=VacuumService
,D/dalvikvm( 5248): GC_FOR_ALLOC freed 5048K, 30% free 16773K/23932K, paused 35ms, total 35ms
,I/dalvikvm-heap( 5248): Grow heap (frag case) to 21.480MB for 2459024-byte allocation
,D/dalvikvm( 5248): GC_FOR_ALLOC freed 3768K, 34% free 17454K/26336K, paused 31ms, total 31ms
,D/dalvikvm( 5248): GC_FOR_ALLOC freed 1222K, 35% free 17360K/26336K, paused 27ms, total 27ms
,W/jxcore-log( 5248): Initializing JXcore engine
,W/jxcore-log( 5248): JXcore engine is ready
,W/jxcore-log( 5248): Starting JXcore engine
,W/jxcore-log( 5248): Platform android
W/jxcore-log( 5248): 
,W/jxcore-log( 5248): Process ARCH arm
W/jxcore-log( 5248): 
,I/jxcore-log( 5248): JXcore Cordova bridge is ready!
I/jxcore-log( 5248): 
,W/jxcore-log( 5248): JXcore engine is started
,I/chromium( 5248): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5248): Error!: missing ) after argument list
E/jxcore  ( 5248): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5248): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1065): isPcwEnable = null
I/ActivityManager(  735): Killing 4429:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,D/CustomFrequencyManagerService(  735): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  pkgName : ACTIVITY_RESUME_BOOSTER@5
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  735): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=17 Removed NainActivit (7/11)
I/SurfaceFlinger(  246): id=17 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/SMD     (  240): DCD ON
,D/SurfaceWidgetView( 1251): destroyHardwareResources():1125914800
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1251): onRestart, Launcher: 1113978816
D/Launcher( 1251): onStart, Launcher: 1113978816
,D/Launcher.HomeView( 1251): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1447): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  246): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=20 createSurf (707x984),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  735): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  735): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1251): onStop
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  735): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/GAV2    ( 5229): Thread[GAThread,5,main]: No campaign data found.
,D/CustomFrequencyManagerService(  735): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 735  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 310, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  735): mCoverManager.getCoverState() : true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/HarmonyEASService(  735): Updating for all 1
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 4
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 290, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): waitForAlarm result :4
,V/AlarmManager(  735): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4078): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 4078): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4078): Breath 90178 latestRequest time : 1449588488423 current time : 1449588578601
,E/SMD     (  240): DCD ON
,D/Finsky  ( 3707): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3707): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService(  735): [PWL] Off : 105s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 5
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  735): waitForAlarm result :8
,D/Headlines( 4078): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4078): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4078): Breath 120034 latestRequest time : 1449588488423 current time : 1449588608457
,D/Headlines( 4078): stop 
,D/Headlines( 4078): Breath.onDestroy : 
,I/ActivityManager(  735): Killing 4444:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 7
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/dalvikvm(  735): GC_CONCURRENT freed 3708K, 58% free 23646K/55172K, paused 34ms+44ms, total 484ms
,E/Watchdog(  735): !@Sync 8
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  735): [PWL] Off : 225s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 9
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  735): initializing...
,I/TLC_TIMA_PKM_initialize(  735): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  735): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  735): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  735): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  735): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  735): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  735): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  735): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  735): App is not loaded in QSEE
,D/QSEECOMAPI: (  735): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  735): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  735): Trustlet response is completed
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 275s ago
,I/PowerManagerService(  735): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  735): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  735): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=735, ws=null) (elapsedTime=3585)
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  735): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :4
,V/AlarmManager(  735): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5451): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5451):  
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  240): DCD ON
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5451): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5451):  
I/SELinux ( 5451):  
,I/SELinux ( 5451): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5451): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5451): >>>>> Normal User
,E/dalvikvm( 5451): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5451): [DEBUG] seapp_context_lookup: seinfoCategory = default
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/TimaKeyStoreProvider( 5451): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5451): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5451): Added TimaKesytore provider
,W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5451, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  735): Killing 4467:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/AmoledAdjustTimer(  735): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 11
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,E/SMD     (  240): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 12
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 13
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 390s ago
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 14
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AmoledAdjustTimer(  735): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
I/PowerManagerService(  735): [PWL] Off : 455s ago
,E/Watchdog(  735): !@Sync 16
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 17
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 18
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 19
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  735): !@Sync 20
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 600s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 21
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 22
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  735): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  735): <AppSync3 Whitelist>
,V/AlarmManager(  735): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 23
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  735): GC_CONCURRENT freed 3584K, 57% free 23514K/54616K, paused 19ms+32ms, total 419ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 24
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 25
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 26
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 27
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 28
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 29
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 855s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 30
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 31
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :4
,I/SensorManagerA(  735): getReportingMode :: sensor.mType = 5
,D/LightsService(  735): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  735): LightSensor setDelay = 200000000
D/Sensors (  735): LightSensor setSensorDelay = 200000000
D/Sensors (  735): Light sensor flush: not enabled 0
D/Sensors (  735): LightSensor enable = 1
D/Sensors (  735): LightSensor enableSensor = 1
,D/SensorManager(  735): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  735): LightSensor enable = 0
,D/Sensors (  735): LightSensor enableSensor = 0
,D/SensorManager(  735): unregisterListener ::   
D/LightsService(  735): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  735): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/UdcCache:FPQuery( 1784): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1297): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ConnectivityService(  735): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/PhenotypeFlagCommitter( 1297): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1297): Using platform SSLCertificateSocketFactory
,W/Uploader( 1297):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1297): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 1297): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1297): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1297): VFY: replacing opcode 0x6e at 0x0033
,I/System.out( 1297): Thread-118(HTTPLog):isShipBuild true
,I/System.out( 1297): Thread-118(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1297): GC_CONCURRENT freed 1756K, 39% free 11295K/18464K, paused 7ms+6ms, total 60ms
,D/dalvikvm( 1297): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/GetCommittedConfigurationOperation( 1297): no corresponding serverToken: com.google.android.gms.playlog.uploader
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 32
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 33
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 34
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 35
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  735): [PWL] Off : 1050s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 36
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 37
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm(  735): GC_CONCURRENT freed 3413K, 57% free 23510K/54616K, paused 39ms+37ms, total 485ms
,E/Watchdog(  735): !@Sync 38
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 39
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  735): [PWL] Off : 1155s ago
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 40
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 41
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 42
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  735): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  735): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  735): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  735): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 43
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 44
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 45
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 46
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1380s ago
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  735): !@Sync 47
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 48
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 49
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 50
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1500s ago
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 51
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 52
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 53
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  735): GC_CONCURRENT freed 3390K, 57% free 23519K/54616K, paused 19ms+33ms, total 420ms
,E/Watchdog(  735): !@Sync 54
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  735): [PWL] Off : 1625s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 55
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 56
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 57
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 58
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  735): !@Sync 59
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 60
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  735): Prepared write state in 115ms
,I/ProcessStatsService(  735): Prepared write state in 105ms
,I/ProcessStatsService(  735): Prepared write state in 40ms
,I/ProcessStatsService(  735): Pruning old procstats: /data/system/procstats/state-2015-12-07-16-12-18.bin
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 61
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :4
,I/SensorManagerA(  735): getReportingMode :: sensor.mType = 5
,D/LightsService(  735): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  735): LightSensor setDelay = 200000000
D/Sensors (  735): LightSensor setSensorDelay = 200000000
D/Sensors (  735): Light sensor flush: not enabled 0
D/Sensors (  735): LightSensor enable = 1
D/Sensors (  735): LightSensor enableSensor = 1
D/SensorManager(  735): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
V/NetworkStats(  735): performPollLocked(flags=0x3)
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): stay LED for fully charged
,V/AlarmManager(  735): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  735): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/LightsService(  735): [SvcLED]  onSensorChanged::light value = 0
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/Sensors (  735): LightSensor enable = 0
D/Sensors (  735): LightSensor enableSensor = 0
,D/SensorManager(  735): unregisterListener ::   
D/LightsService(  735): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
V/NetworkStats(  735): performPollLocked() took 216ms
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
,I/EventLogService( 1784): Aggregate from 1449588482575 (log), 1449588482575 (data)
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1297): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  735): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 1297): GC_CONCURRENT freed 1892K, 39% free 11408K/18464K, paused 13ms+6ms, total 53ms
,W/PhenotypeConfigurator( 1297): Server returned 404
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/ActivityManager(  735): Killing 4646:com.android.providers.calendar/u0a44 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4621:com.sec.android.app.voicenote/1000 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4604:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1801s
,I/ActivityManager(  735): Killing 4483:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty for 1802s
,E/SMD     (  240): DCD ON
,I/ActivityManager(  735): Killing 4769:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 2996:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4693:com.google.android.talk/u0a105 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 3928:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4797:com.wssyncmldm/1000 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4650:com.sec.providers.settingsearch/u0a160 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4410:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4197:com.android.calendar/u0a142 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4599:com.sec.phone/1001 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 4550:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1800s
,I/ActivityManager(  735): Killing 3885:com.google.android.music:main/u0a122 (adj 15): empty for 1800s
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 62
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,V/AlarmManager(  735): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  735): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  735): <AppSync3 Whitelist>
,V/AlarmManager(  735): (AppSync) com.google.android.gms : 900(900)
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  735): (AppSync) ### 1 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 63
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1890s ago
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  735): !@Sync 64
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  735): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  735): stay LED for fully charged
,D/UiModeManager(  735): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  735): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AmoledAdjustTimer(  735): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
E/SMD     (  240): DCD ON
E/SMD     (  240): DCD ON
D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  735): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 1950): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1950): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
D/AndroidRuntime( 5882): 
D/AndroidRuntime( 5882): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5882): CheckJNI is OFF
D/AndroidRuntime( 5882): setted country_code = Poland
D/AndroidRuntime( 5882): setted countryiso_code = PL
D/AndroidRuntime( 5882): setted sales_code = XEO
D/AndroidRuntime( 5882): readGMSProperty: start
D/AndroidRuntime( 5882): readGMSProperty: already setted!!
D/AndroidRuntime( 5882): readGMSProperty: end
D/AndroidRuntime( 5882): addProductProperty: start
D/dalvikvm( 5882): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5882): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5882): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5882): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5882): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5882): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5882): failed to load memtrack module: -2
D/dalvikvm( 5882): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5882): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  735): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  735): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  735): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  735): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  735): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  735): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  735): START PACKAGE DELETE: observer{1130208392}
D/PackageManager(  735): pkg{<packageName>}
D/PackageManager(  735): user{0}
D/PackageManager(  735): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  735): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  735): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  735): getApplicationUninstallationEnabled
D/ApplicationPolicy(  735): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  735): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  735): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  735): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  735): Killing 5248:com.test.thalitest/u0a179 (adj 11): stop com.test.thalitest
I/ActivityManager(  735): Killing 5172:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1835s
I/ActivityManager(  735): Killing 4008:com.sec.spp.push/u0a38 (adj 15): empty for 1835s
I/ActivityManager(  735): Killing 5153:com.policydm/1000 (adj 15): empty for 1835s
I/ActivityManager(  735): Killing 4216:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1836s
I/ActivityManager(  735): Killing 5136:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1836s
I/ActivityManager(  735): Killing 5122:com.sec.pcw.device/1000 (adj 15): empty for 1836s
I/ActivityManager(  735): Killing 5108:com.android.musicfx/u0a24 (adj 15): empty for 1836s
I/ActivityManager(  735): Killing 5095:com.samsung.groupcast/u0a15 (adj 15): empty for 1836s
I/ActivityManager(  735): Killing 5078:com.google.android.partnersetup/u0a14 (adj 15): empty for 1836s
I/ActivityManager(  735): Killing 5062:com.sec.android.inputmethod/1000 (adj 15): empty for 1837s
I/ActivityManager(  735): Killing 5010:com.android.defcontainer/u0a6 (adj 15): empty for 1837s
D/dalvikvm(  735): GC_CONCURRENT freed 3486K, 57% free 23558K/54404K, paused 7ms+10ms, total 117ms
D/dalvikvm(  735): WAIT_FOR_CONCURRENT_GC blocked 97ms
W/PackageSettings(  735): Skipping PackageSetting{42c5d8d8 com.example.hello/10180} due to missing metadata
D/PackageManager(  735): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  735): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3325): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 5908): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5908):  
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "sms"
D/dalvikvm( 1405): GC_EXPLICIT freed 4285K, 46% free 10018K/18464K, paused 3ms+4ms, total 67ms
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2188): GC_EXPLICIT freed 988K, 41% free 10995K/18464K, paused 3ms+7ms, total 91ms
D/RCPManagerService(  735): PackageReceiver onReceive()
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "smsto"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5908): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5908):  
I/SELinux ( 5908):  
I/SELinux ( 5908): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5908): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5908): >>>>> Normal User
E/dalvikvm( 5908): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5908): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "mms"
I/HarmonyEASService(  735): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5908): in addTimaSignatureService
D/TimaKeyStoreProvider( 5908): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5908): Added TimaKesytore provider
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "mmsto"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "sms"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "smsto"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "mms"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "mmsto"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  735): Package has changed for user 0
D/EnterpriseDeviceManagerService(  735): Admin package name: com.google.android.gms
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5908, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 5908): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5908): ELMEngine.ELMEngine( context ).
D/elm:14132( 5908): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5908): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5908): ElmAgentService : onCreate()
D/dalvikvm(  735): GC_EXPLICIT freed 1495K, 57% free 23513K/54404K, paused 6ms+18ms, total 262ms
D/elm:14132( 5908): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5908): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5908): MDMBridge.getInstance()
D/elm:14132( 5908): MDMBridge.getAllLicenseInfoFromSDK()
D/PackageManager(  735): delete sourFile : 
D/elm:14132( 5908): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5921): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5921):  
D/PackageManager(  735): delete native library directory: 
D/elm:14132( 5908): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5908): ElmAgentService : onDestroy().
D/dalvikvm(  248): GC_EXPLICIT freed 43K, 49% free 9509K/18464K, paused 2ms+2ms, total 27ms
D/PackageManager(  735): return delete result to caller: 1130208392
D/PackageManager(  735): returnCode: 1
D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/ActivityManager(  735): Killing 4025:com.osp.app.signin/u0a43 (adj 15): empty for 1836s
V/BackupManagerService(  735): removePackageParticipantsLocked: uid=10179 #1
D/AndroidRuntime( 5882): Shutting down VM
D/dalvikvm( 5882): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5921): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5921):  
I/SELinux ( 5921):  
I/SELinux ( 5921): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5921): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5921): >>>>> Normal User
E/dalvikvm( 5921): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 5921): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9509K/18464K, paused 1ms+3ms, total 26ms
D/TimaKeyStoreProvider( 5921): in addTimaSignatureService
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "sms"
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9509K/18464K, paused 2ms+3ms, total 21ms
D/TimaKeyStoreProvider( 5921): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5921): Added TimaKesytore provider
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SMD     (  240): DCD ON
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "smsto"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "mms"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  735):   Action: "android.intent.action.SENDTO"
I/PackageManager(  735):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  735):   Scheme: "mmsto"
I/PackageManager(  735): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=5921, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5921): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425c1ad0, skipping init
I/SecureStorage( 5921): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 5921): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  379): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5921
I/SecureStorage(  379): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 5921): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 5921): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  379): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5921
I/SecureStorage(  379): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  735): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  735): clearDefaults: com.test.thalitest
D/InputReader(  735): Processing first event
I/EventHub(  735): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  735): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=217 classes=0x94
I/EventHub(  735): Removing device '/dev/input/event1' due to inotify event
I/InputReader(  735): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  735): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  735): MultiTouchMotionAccumulator: initial slot number is -1
I/ActivityManager(  735): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/InputDispatcher(  735): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  246): id=21 createSurf (720x1280),2 flag=404, TcreenshotS
D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (178 us)
D/Mms/MmsApp( 4324): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/Mms/MmsApp( 4324): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
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
