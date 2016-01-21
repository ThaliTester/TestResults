#### Test 56449660311ec66_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
W/System.err( 6661): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 6661): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6661): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6661): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 6661): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 6661): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6661): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6661): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6661): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6661): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6661): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6661): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6661): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6661): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6661): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6661): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6661): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 6661): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6661): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6661): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6661): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6661): 	... 21 more
D/GalaxyFinderApplication( 6661): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 6661): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 6679): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6679):  
--------- beginning of /dev/log/system
I/ActivityManager( 2421): Killing 5925:com.samsung.android.magazine.service/u0a110 (adj 15): empty #43
I/SELinux ( 6679): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6679):  
I/SELinux ( 6679):  
I/SELinux ( 6679): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6679): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6679): >>>>> Normal User
E/dalvikvm( 6679): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 6679): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6679): in addTimaSignatureService
D/TimaKeyStoreProvider( 6679): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6679): Added TimaKesytore provider
D/dalvikvm( 6679): GC_CONCURRENT freed 2991K, 30% free 9579K/13560K, paused 3ms+1ms, total 19ms
D/dalvikvm( 6679): WAIT_FOR_CONCURRENT_GC blocked 14ms
I/SELinux ( 6695): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6695):  
I/ActivityManager( 2421): Killing 5258:com.android.email/u0a157 (adj 15): empty #43
V/AlarmManager( 2421): waitForAlarm result :4
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/SELinux ( 6695): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6695):  
I/SELinux ( 6695):  
I/SELinux ( 6695): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6695): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6695): >>>>> Normal User
E/dalvikvm( 6695): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6695): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6695): in addTimaSignatureService
D/TimaKeyStoreProvider( 6695): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6695): Added TimaKesytore provider
D/dalvikvm( 6679): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42243138, skipping init
I/SecureStorage( 6679): [INFO]: SPID(0x00000000)Processing data
D/dalvikvm( 6695): GC_CONCURRENT freed 2989K, 30% free 9572K/13556K, paused 2ms+2ms, total 18ms
D/dalvikvm( 6695): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)Credentials: uid 1000, gid 1000, pid 6679
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)Received function mask & code: 00000106
D/ActivityThread( 6695): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6695): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager( 2421): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6695): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/SA      ( 5842): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5842): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5842): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5733): loadAuthorityPref(): sEnableAuthority = true
W/ContextImpl( 6396): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/Icing.InternalIcingCorporaProvider( 6461): Updating corpora: A: com.test.thalitest, C: MAYBE
I/SELinux ( 6724): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6724):  
I/SELinux ( 6724): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6724):  
I/SELinux ( 6724):  
I/SELinux ( 6724): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6724): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6724): >>>>> Normal User
E/dalvikvm( 6724): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6724): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6724): in addTimaSignatureService
D/TimaKeyStoreProvider( 6724): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6724): Added TimaKesytore provider
D/dalvikvm( 6724): GC_CONCURRENT freed 2993K, 30% free 9579K/13564K, paused 11ms+1ms, total 55ms
D/dalvikvm( 6724): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/CapabilityManagerService New( 6724): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 6737): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6737):  
D/AndroidRuntime( 6720): 
D/AndroidRuntime( 6720): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6720): CheckJNI is OFF
D/AndroidRuntime( 6720): setted country_code = Poland
D/AndroidRuntime( 6720): setted countryiso_code = PL
D/AndroidRuntime( 6720): setted sales_code = PLS
D/AndroidRuntime( 6720): readGMSProperty: start
D/AndroidRuntime( 6720): readGMSProperty: already setted!!
D/AndroidRuntime( 6720): readGMSProperty: end
D/AndroidRuntime( 6720): addProductProperty: start
D/dalvikvm( 6720): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6720): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6720): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6720): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6720): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 6737): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6737):  
I/SELinux ( 6737):  
I/SELinux ( 6737): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6737): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6737): >>>>> Normal User
E/dalvikvm( 6737): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6737): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2421): Killing 5359:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
D/TimaKeyStoreProvider( 6737): in addTimaSignatureService
D/TimaKeyStoreProvider( 6737): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6737): Added TimaKesytore provider
D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
E/memtrack( 6720): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6720): failed to load memtrack module: -2
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)PID: 6679, TID: 6691
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/dalvikvm( 6720): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 6737): GC_CONCURRENT freed 2997K, 30% free 9569K/13560K, paused 10ms+1ms, total 41ms
D/dalvikvm( 6737): WAIT_FOR_CONCURRENT_GC blocked 30ms
D/PackageIntentReceiver( 6737): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6737): Not GearManger package! 
I/SELinux ( 6759): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6759):  
I/ActivityManager( 2421): Killing 5797:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
I/Icing.InternalIcingCorporaProvider( 6461): UpdateCorporaTask done [took 587 ms] updated apps [took 587 ms] 
I/ActivityManager( 2421): Killing 5602:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/AndroidRuntime( 6720): Calling main entry com.android.commands.am.Am
I/SELinux ( 6759): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6759):  
I/SELinux ( 6759):  
I/SELinux ( 6759): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6759): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6759): >>>>> Normal User
E/dalvikvm( 6759): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6759): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 6759): in addTimaSignatureService
D/TimaKeyStoreProvider( 6759): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6759): Added TimaKesytore provider
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SecureStorage( 6679): [INFO]: SPID(0x00000000)Processing data has been completed
I/SELinux ( 6773): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6773):  
D/dalvikvm( 6759): GC_CONCURRENT freed 2994K, 30% free 9577K/13564K, paused 3ms+1ms, total 33ms
D/dalvikvm( 6759): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6720): Shutting down VM
D/MagazineService Version( 6759): Magazine-Channel: 13
D/dalvikvm( 6720): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
D/MagazineService Version( 6759): Magazine-Provider: 13
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9505K/10540K, paused 2ms+3ms, total 37ms
I/SELinux ( 6773): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6773):  
I/SELinux ( 6773):  
I/SELinux ( 6773): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6773): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6773): >>>>> Normal User
E/dalvikvm( 6773): >>>>> com.test.thalitest [ userId:0 | appId:10642 ]
E/SELinux ( 6773): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/MagazineService Version( 6759): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 6759): [onCreate]
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9505K/10540K, paused 2ms+3ms, total 24ms
D/TimaKeyStoreProvider( 6773): in addTimaSignatureService
D/TimaKeyStoreProvider( 6773): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6773): Added TimaKesytore provider
D/MagazineService::MagazineBroadcastReceiver( 6759): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9505K/10540K, paused 2ms+3ms, total 24ms
I/SQLiteSecureOpenHelper( 4162): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4162): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
I/MagazineService::MagazineService( 6759): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 6786): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6786):  
D/MagazineService::MagazineService( 6759): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager( 2421): Killing 6057:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 6786): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6786):  
I/SELinux ( 6786):  
I/SELinux ( 6786): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6786): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6786): >>>>> Normal User
E/dalvikvm( 6786): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 6786): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6786): in addTimaSignatureService
D/TimaKeyStoreProvider( 6786): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6786): Added TimaKesytore provider
D/dalvikvm( 6773): GC_CONCURRENT freed 2998K, 30% free 9575K/13564K, paused 3ms+2ms, total 24ms
D/dalvikvm( 6773): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 6786): GC_CONCURRENT freed 2996K, 30% free 9573K/13560K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 6786): WAIT_FOR_CONCURRENT_GC blocked 19ms
,V/WebViewChromium( 6773): Binding Chromium to the background looper Looper (main, tid 1) {4224f138}
,I/chromium( 6773): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6773): Initializing chromium process, renderers=0
,W/chromium( 6773): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6773): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6773): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6773): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6773): Mali API Version : 401
,I/Mali    ( 6773): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6773): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6773): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6773): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6773): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6773): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6773): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2421): tr p:6773,o:f
W/dalvikvm( 6773): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6773): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6773): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6773): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6773): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6773): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6773): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6773): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6773): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6773): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6773): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6773): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6773): CordovaWebView is running on device made by: samsung
,I/SELinux ( 6819): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6819):  
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:6773,o:f
I/ActivityManager( 2421): Killing 5812:com.sec.android.soagent/u0a38 (adj 15): empty #43
,I/SELinux ( 6819): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6819):  
I/SELinux ( 6819):  
,I/SELinux ( 6819): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6819): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6819): >>>>> Normal User
,E/dalvikvm( 6819): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 6819): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6773): EGLImpl-HWUI Protected EGL context created
,D/TimaKeyStoreProvider( 6819): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6819): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6819): Added TimaKesytore provider
,D/OpenGLRenderer( 6773): Enabling debug mode 0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 6773): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 6773): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6819): GC_CONCURRENT freed 2994K, 30% free 9569K/13556K, paused 6ms+1ms, total 24ms
,D/dalvikvm( 6819): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/KidsPlatformStub( 6819): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6840): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6840):  
I/ActivityManager( 2421): Killing 6147:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,I/SELinux ( 6840): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6840):  
I/SELinux ( 6840):  
,I/SELinux ( 6840): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 6840): >>>>> Normal User
,E/dalvikvm( 6840): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6840): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6840): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6840): Added TimaKesytore provider
,D/dalvikvm( 6840): GC_CONCURRENT freed 2998K, 30% free 9572K/13560K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 6840): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Icing   ( 3439): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,I/SELinux ( 6854): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6854):  
I/ActivityManager( 2421): Killing 5878:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
,I/SELinux ( 6854): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6854):  
I/SELinux ( 6854):  
,I/SELinux ( 6854): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6854): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 6854): >>>>> Normal User
,E/dalvikvm( 6854): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6854): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6854): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6854): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6854): Added TimaKesytore provider
,D/JsMessageQueue( 6773): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6854): GC_CONCURRENT freed 3002K, 30% free 9570K/13564K, paused 5ms+2ms, total 46ms
,D/dalvikvm( 6854): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/Icing   ( 3439): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/UMC:Core( 6854): onCreate(): ,
,D/dalvikvm( 6773): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42247b08,
,D/dalvikvm( 6773): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42247b08,
,D/jxcore_app_log( 6773): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2031468336,
,I/chromium( 6773): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/USER_AGENT( 6854): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0,
,D/dalvikvm( 6773): GC_CONCURRENT freed 1316K, 17% free 11334K/13636K, paused 2ms+2ms, total 30ms,
,D/dalvikvm( 6773): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/[SAMSUNG SMARCART NATIVE]( 6854): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6854): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so ,
I/TZ_CCM_C_GetFunctionList: ( 6854): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6854): FINISHED: initialize rv:0,
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 6854): GC_CONCURRENT freed 1856K, 21% free 10786K/13628K, paused 3ms+7ms, total 52ms,
,D/dalvikvm( 6854): WAIT_FOR_CONCURRENT_GC blocked 7ms,
,D/UMC:SecurityUtils( 6854): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6854): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6854): New Flow,
I/        ( 2421): CCM JNI: In ccm_register_for_default_cert
I/        ( 2421): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2421): &ctx = 0x7bc64618
I/TLC_TZ_CCM: ( 2421): creating new ccm context...
I/TLC_TZ_CCM: ( 2421): initializing ccm context...
,I/TLC_TZ_CCM: ( 2421): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2421): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2421): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2421): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2421): root = 0, root_len = 1
I/TZ: client_server_communication( 2421): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2421): aligned max_sendmsg_size = 19456
,I/TZ: client_server_communication( 2421): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2421): Client_Server_Open was called
I/TZ: client_server_communication( 2421): IClientServer::IClientServer()
,I/TZ: client_server_communication( 2421): BpClientServer::BpClientServer(),
D/TimaService( 2421): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2421): TIMA: in getTimaVersion,
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2510): creating new ccm context...
I/TZ_CCM_SERVER( 2510): initializing ccm context...
I/TZ_CCM_SERVER( 2510): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2510): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2510): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2510): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2510): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2510): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2510): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2510): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2510): device_id = 0x0
I/TZ: mc_tlc_communication( 2510): tlc_open() was called
I/TZ: mc_tlc_communication( 2510): Opening MobiCore device
I/TZ: mc_tlc_communication( 2510): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2510): Opening the session
,I/TZ: mc_tlc_communication( 2510): tlc_open() succeeded,
I/TZ: client_server_communication( 2421): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2421): ctx = 0x850fcfd0, comm = 0x81d12aa0, sendmsg = 0x81d1a008, recvmsg = 0x81d1ec08
I/TZ_init: ( 2421): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456,
E/Parcel  ( 2421): nm 19456
E/TZ_init: ( 2421): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2421): trustlet initialization failed
,I/TZ_init: ( 2421): TZ_init_START...
I/TZ_init: ( 2421): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2421): nm 19456
I/TZ_init: ( 2421): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2421): Exercising TZ_DB_INIT in TLC
,I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2421): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2421): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: ( 2421): Exercising TZ_CCM_register_default_TLC
,I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2421): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2421): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2421): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: ( 2421): Exercising TZ_CCM_C_Finalize_TLC
,I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2421): nm 19456
I/TZ: client_server_communication( 2421): Client_Server_Close was called
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2510): tlc_close() was called
,I/TZ: mc_tlc_communication( 2510): Closing the session
,I/TZ: mc_tlc_communication( 2510): Free WSM
,I/TZ: mc_tlc_communication( 2510): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2510): tlc_close() succeeded
,I/TZ: client_server_communication( 2421): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6854): TIMA service call for password change success!!
,D/UMC:AdminManager( 6854): init - start
,D/UMC:AdminManager( 6854): loadAdmins
,D/UMC:AdminManager( 6854): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6854): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6854): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6854): init - end
,V/UMC:AlarmHandler( 6854): Enter loadList
,D/EnterpriseDeviceManagerService( 2421): Creating context as user 0
,D/SPPApp  ( 6854): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6854): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/dalvikvm( 6773): GC_CONCURRENT freed 1709K, 16% free 15137K/17816K, paused 2ms+4ms, total 48ms
,I/SELinux ( 6870): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6870):  
I/ActivityManager( 2421): Killing 6168:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,I/SELinux ( 6870): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6870):  
I/SELinux ( 6870):  
,I/SELinux ( 6870): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6870): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6870): >>>>> Normal User
,E/dalvikvm( 6870): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6870): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6870): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6870): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6870): Added TimaKesytore provider
,D/dalvikvm( 6870): GC_CONCURRENT freed 2999K, 30% free 9576K/13564K, paused 5ms+1ms, total 25ms
,D/dalvikvm( 6870): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/ApplicationPromenada( 6870): Application OnCreate start
,D/ApplicationPromenada( 6870): Application OnCreate po on Create
D/CrashReporter( 6870): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42237820
D/CrashReporter( 6870): Swaping uncaught exception handler
,D/ApplicationPromenada( 6870): Application OnCreate App Loader start
,D/ApplicationPromenada( 6870): Application OnCreate App Loader finish
,D/p2.ApplicationLoader( 6870): ############################## cached apps: 
,V/WebViewChromium( 6870): Binding Chromium to the background looper Looper (main, tid 1) {422492f8}
,I/chromium( 6870): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6870): Initializing chromium process, renderers=0
,W/chromium( 6870): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6870): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6870): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6870): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6870): Mali API Version : 401
,I/Mali    ( 6870): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 360, Delta = 10
,D/ApplicationPromenada( 6870): Application OnCreate Finish
,I/ActivityManager( 2421): Killing 6180:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/PackageBroadcastService( 3439): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3439): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3439): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3439): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3439): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3439): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3439): Submit a task: k
,D/ChimeraCfgMgr( 3439): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3439): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3439): Processing package: com.test.thalitest
,D/GassUtils( 3439): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3439): Found info for package com.test.thalitest in db.
,D/dalvikvm( 6773): GC_FOR_ALLOC freed 5770K, 29% free 16766K/23560K, paused 51ms, total 51ms
,D/Headlines( 5905): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5905): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5905): Breath 76173 latestRequest time : 1453367889978 current time : 1453367966151
,D/Finsky  ( 3700): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,I/VacuumService( 2735): Vacuum at: now=1453367966413 tag=VacuumService
,D/dalvikvm( 6870): GC_CONCURRENT freed 1785K, 21% free 10820K/13592K, paused 3ms+3ms, total 64ms
,D/dalvikvm( 6773): GC_FOR_ALLOC freed 3143K, 28% free 17122K/23560K, paused 44ms, total 49ms
,D/dalvikvm( 2421): GC_EXPLICIT freed 27579K, 72% free 25455K/89476K, paused 18ms+20ms, total 325ms
,I/Icing   ( 3439): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/dalvikvm( 6773): GC_FOR_ALLOC freed 4571K, 24% free 18085K/23680K, paused 47ms, total 58ms
,I/dalvikvm-heap( 6773): Grow heap (frag case) to 22.140MB for 3688532-byte allocation
,I/PhenotypeConfigurator( 2735): Scheduling Phenotype for one-off execution 2924 seconds from now (1453367967343)
,I/Icing   ( 3439): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 6773): GC_FOR_ALLOC freed 2454K, 30% free 19233K/27284K, paused 46ms, total 46ms
,D/GetConfigurationSnapshotOperation( 2735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2735): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 6870): GC_CONCURRENT freed 2340K, 25% free 10418K/13760K, paused 3ms+2ms, total 28ms
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 2735): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x003d
,W/ResourceType( 6870): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6870): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6870): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6870): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6870): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6870): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6870): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6870): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6870): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6870): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6870): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6870): 	at java.lang.Thread.run(Thread.java:841)
,I/System.out( 2735): Thread-119(HTTPLog):isShipBuild true
,I/System.out( 2735): Thread-119(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/jxcore-log( 6773): Initializing JXcore engine
,W/jxcore-log( 6773): JXcore engine is ready
,W/jxcore-log( 6773): Starting JXcore engine
,D/dalvikvm( 2735): GC_FOR_ALLOC freed 1508K, 20% free 11700K/14540K, paused 42ms, total 45ms
,W/jxcore-log( 6773): Platform android
W/jxcore-log( 6773): 
,W/jxcore-log( 6773): Process ARCH arm
W/jxcore-log( 6773): 
,D/dalvikvm( 6870): GC_CONCURRENT freed 2076K, 25% free 10368K/13760K, paused 2ms+11ms, total 56ms
,I/jxcore-log( 6773): JXcore Cordova bridge is ready!
I/jxcore-log( 6773): 
,W/jxcore-log( 6773): JXcore engine is started
D/p2.ApplicationLoader( 6870): Process time: 3459
,D/p2.ApplicationLoader( 6870): ##############################  apps after loading: 
,E/jxcore  ( 6773): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6773): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6773): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2421): Killing 5347:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4719): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4719): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4719): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:418][onResume] Postpone Count : 30
,I/DBG_DM  ( 4719): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4719): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
,I/DBG_DM  ( 4719): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,D/dalvikvm( 6870): GC_CONCURRENT freed 2194K, 27% free 10099K/13760K, paused 3ms+4ms, total 55ms
,I/DBG_DM  ( 4719): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4719): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4719): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4719): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4719): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4719): setTransGradationMode to true
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4719): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2421): semi p:4719,o:t
,I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6773): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/HarmonyEASService( 2421): Updating for all 1
,D/PackageManager( 2421): [MSG] SEND_PENDING_BROADCAST,
,D/PackageManager( 2421): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@43011ed8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}],
,I/InputReader( 2421): Reconfiguring input devices.  changes=0x00000010,
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto",
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO",
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2421):   Scheme: "mms"
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto",
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RegisteredServicesCache( 2768): empty dynamic service,
,I/Icing.InternalIcingCorporaProvider( 6461): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "sms"
,I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "smsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/FileShare-Server( 4853): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mms"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2421):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2421):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2421):   Scheme: "mmsto"
I/PackageManager( 2421): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/SSRMv2:SIOP( 2421): SIOP:: AP = 360, Delta = 0
D/BezelQuickConnect( 5183): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
D/BezelQuickConnect( 5183): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
I/Icing.InternalIcingCorporaProvider( 6461): UpdateCorporaTask done [took 233 ms] updated apps [took 232 ms] 
D/PackageBroadcastService( 3439): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2421): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ApplicationsProvider( 2954): Could not fetch usage stats
W/ApplicationsProvider( 2954): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2954): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2954): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2954): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/Icing   ( 3439): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms,
,I/Icing   ( 3439): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8,
,V/AlarmManager( 2421): waitForAlarm result :8,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2421): waitForAlarm result :4
,D/Headlines( 5905): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5905): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5905): Breath 91153 latestRequest time : 1453367889978 current time : 1453367981131
,D/dalvikvm( 3700): GC_CONCURRENT freed 8103K, 36% free 16262K/25352K, paused 4ms+7ms, total 111ms
,D/dalvikvm( 3700): WAIT_FOR_CONCURRENT_GC blocked 98ms
,D/Finsky  ( 3700): [190] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3700): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2421): !@Sync 5,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = -20,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 105s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5905): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5905): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5905): Breath 120030 latestRequest time : 1453367889978 current time : 1453368010008,
,D/Headlines( 5905): stop ,
,D/Headlines( 5905): Breath.onDestroy : ,
,I/ActivityManager( 2421): Killing 6208:com.sec.android.app.sns3/u0a37 (adj 15): empty #43,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 6,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2421): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2421): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2421): !@Sync 7,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2421): !@Sync 8,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2421): !@Sync 9,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 4241K, 72% free 25211K/89476K, paused 204ms, total 204ms,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 2421): GC_CONCURRENT freed 481K, 73% free 24780K/89476K, paused 12ms+17ms, total 228ms,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2421): initializing...,
I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2421): device_id = 0x0
I/TZ: mc_tlc_communication( 2421): tlc_open() was called
,I/TZ: mc_tlc_communication( 2421): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2421): Opening the session
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed
,E/Watchdog( 2421): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3994): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 275s ago,
,E/Watchdog( 2421): !@Sync 11,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7728): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7728):  
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7728): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7728):  
I/SELinux ( 7728):  
,I/SELinux ( 7728): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7728): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7728): >>>>> Normal User
,E/dalvikvm( 7728): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7728): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7728): in addTimaSignatureService
D/TimaKeyStoreProvider( 7728): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7728): Added TimaKesytore provider
,D/dalvikvm( 7728): GC_CONCURRENT freed 3009K, 30% free 9568K/13564K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7728): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2421): Killing 6278:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/EventLogService( 3439): Aggregate from 1453366248444 (log), 1453366248444 (data)
,D/dalvikvm( 3439): GC_CONCURRENT freed 2124K, 20% free 12670K/15780K, paused 6ms+10ms, total 92ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 12
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5570): [b] __PingReply__
,I/PowerManagerService( 2421): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 13
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 14
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 15
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 16
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2421): [PWL] Off : 455s ago
,E/Watchdog( 2421): !@Sync 17
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 18
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 19
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2421): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 21
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2421): [PWL] Off : 600s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 39
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/GAV2    ( 5666): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5666): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2421): !@Sync 22
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/dalvikvm( 2421): GC_CONCURRENT freed 3645K, 73% free 24872K/88868K, paused 22ms+17ms, total 239ms
,E/Watchdog( 2421): !@Sync 23
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2581): GC_CONCURRENT freed 15750K, 34% free 33859K/50592K, paused 24ms+10ms, total 151ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 24
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 680s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 25
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4067): GC_CONCURRENT freed 2893K, 29% free 9728K/13608K, paused 22ms+3ms, total 89ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 26
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 27
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 28
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 29
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2421): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 855s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 31
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2421): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 32
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,E/SPPClientService( 5570): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 33
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 34
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 35
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 36
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 2421): GC_CONCURRENT freed 3852K, 73% free 24762K/88868K, paused 21ms+17ms, total 255ms
,E/Watchdog( 2421): !@Sync 37
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 38
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 39
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2421): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 41
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 42
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2421): LightSensor setDelay = 200000000
,D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 40
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5570): [b] __PingReply__
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 43
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1265s ago
,E/Watchdog( 2421): !@Sync 44
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 45
,TIME-OUT KILL (timeout was 1200000ms)
```
