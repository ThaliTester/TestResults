#### Test 506502781a07ac8_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 6713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6713):  
I/SELinux ( 6713):  
I/SELinux ( 6713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6713): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6713): >>>>> Normal User
E/dalvikvm( 6713): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6713): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 6713): in addTimaSignatureService
D/TimaKeyStoreProvider( 6713): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6713): Added TimaKesytore provider
,D/dalvikvm( 6697): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42264a28, skipping init
D/dalvikvm( 6713): GC_CONCURRENT freed 2994K, 30% free 9577K/13672K, paused 2ms+1ms, total 20ms
D/dalvikvm( 6713): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/SecureStorage( 6697): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)Credentials: uid 1000, gid 1000, pid 6697
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)Received function mask & code: 00000106
--------- beginning of /dev/log/system
D/ActivityThread( 6713): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ActivityManager( 2400): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SA      ( 5880): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5880): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5880): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5774): loadAuthorityPref(): sEnableAuthority = true
D/AndroidRuntime( 6730): 
D/AndroidRuntime( 6730): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6730): CheckJNI is OFF
D/AndroidRuntime( 6730): setted country_code = Poland
D/AndroidRuntime( 6730): setted countryiso_code = PL
D/AndroidRuntime( 6730): setted sales_code = PLS
D/AndroidRuntime( 6730): readGMSProperty: start
D/AndroidRuntime( 6730): readGMSProperty: already setted!!
D/AndroidRuntime( 6730): readGMSProperty: end
D/AndroidRuntime( 6730): addProductProperty: start
D/dalvikvm( 6730): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6730): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6730): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6730): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6730): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Icing.InternalIcingCorporaProvider( 6502): Updating corpora: A: com.test.thalitest, C: MAYBE
W/ContextImpl( 6434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 6751): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6751):  
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9503K/10648K, paused 2ms+3ms, total 35ms
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 2ms+2ms, total 23ms
I/SELinux ( 6751): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6751):  
I/SELinux ( 6751):  
I/SELinux ( 6751): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6751): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6751): >>>>> Normal User
E/dalvikvm( 6751): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6751): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 2ms+3ms, total 26ms
E/memtrack( 6730): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6730): failed to load memtrack module: -2
D/dalvikvm( 6730): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/TimaKeyStoreProvider( 6751): in addTimaSignatureService
D/TimaKeyStoreProvider( 6751): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6751): Added TimaKesytore provider
D/AndroidRuntime( 6730): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2400): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2400): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2400): mDVFSHelper.acquire()
I/SELinux ( 6767): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6767):  
D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6730): Shutting down VM
I/SELinux ( 6767): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6767):  
I/SELinux ( 6767):  
I/SELinux ( 6767): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6767): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6767): >>>>> Normal User
E/dalvikvm( 6767): >>>>> com.test.thalitest [ userId:0 | appId:10562 ]
E/SELinux ( 6767): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm( 6730): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+1ms, total 5ms
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1959): [INFO]: SPID(0x00000006)PID: 6697, TID: 6709
D/dalvikvm( 6751): GC_CONCURRENT freed 2998K, 30% free 9573K/13668K, paused 11ms+3ms, total 70ms
D/dalvikvm( 6751): WAIT_FOR_CONCURRENT_GC blocked 51ms
D/CapabilityManagerService New( 6751): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
D/TimaKeyStoreProvider( 6767): in addTimaSignatureService
D/TimaKeyStoreProvider( 6767): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6767): Added TimaKesytore provider
I/SELinux ( 6779): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6779):  
I/ActivityManager( 2400): Killing 5401:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
I/SELinux ( 6779): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6779):  
I/SELinux ( 6779):  
I/SELinux ( 6779): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6779): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6779): >>>>> Normal User
E/dalvikvm( 6779): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6779): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/TimaKeyStoreProvider( 6779): in addTimaSignatureService
D/TimaKeyStoreProvider( 6779): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6779): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4174): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4174): getDatabaseLocked(b,b,pwd)...
I/SecureStorage( 6697): [INFO]: SPID(0x00000000)Processing data has been completed
D/dalvikvm( 6767): GC_CONCURRENT freed 3014K, 31% free 9559K/13672K, paused 1ms+1ms, total 21ms
D/dalvikvm( 6767): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 6779): GC_CONCURRENT freed 2994K, 30% free 9567K/13664K, paused 3ms+1ms, total 22ms
D/dalvikvm( 6779): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/PackageIntentReceiver( 6779): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6779): Not GearManger package! 
,I/SELinux ( 6791): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6791):  
I/ActivityManager( 2400): Killing 5835:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
V/WebViewChromium( 6767): Binding Chromium to the background looper Looper (main, tid 1) {422603a8}
I/chromium( 6767): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6767): Initializing chromium process, renderers=0
I/SELinux ( 6791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6791):  
I/SELinux ( 6791):  
I/SELinux ( 6791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6791): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6791): >>>>> Normal User
E/dalvikvm( 6791): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6791): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/chromium( 6767): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/TimaKeyStoreProvider( 6791): in addTimaSignatureService
D/libEGL  ( 6767): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 6767): loaded /system/lib/egl/libGLESv1_CM_mali.so
I/Icing.InternalIcingCorporaProvider( 6502): UpdateCorporaTask done [took 756 ms] updated apps [took 756 ms] 
D/TimaKeyStoreProvider( 6791): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6791): Added TimaKesytore provider
I/ActivityManager( 2400): Killing 5648:com.samsung.klmsagent/u0a18 (adj 15): empty #43
D/libEGL  ( 6767): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6767): Mali API Version : 401
I/Mali    ( 6767): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 6767): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6767): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6767): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6767): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6767): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 6767): VFY: replacing opcode 0x6e at 0x0008
D/StatusBarManagerService( 2400): tr p:6767,o:f
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
W/dalvikvm( 6767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6767): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6767): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6767): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6767): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6767): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6767): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6767): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6767): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6767): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6767): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6767): CordovaWebView is running on device made by: samsung
D/dalvikvm( 6791): GC_CONCURRENT freed 2991K, 30% free 9574K/13668K, paused 4ms+2ms, total 31ms
D/dalvikvm( 6791): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/MagazineService Version( 6791): Magazine-Channel: 13
D/MagazineService Version( 6791): Magazine-Provider: 13
D/MagazineService Version( 6791): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 6791): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 6791): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/MagazineService::MagazineService( 6791): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/StatusBarManagerService( 2400): semi p:6767,o:f
I/SELinux ( 6826): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6826):  
D/MagazineService::MagazineService( 6791): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager( 2400): Killing 6095:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
I/SELinux ( 6826): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6826):  
I/SELinux ( 6826):  
I/SELinux ( 6826): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6826): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6826): >>>>> Normal User
E/dalvikvm( 6826): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
E/SELinux ( 6826): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 6767): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 6767): Enabling debug mode 0
D/TimaKeyStoreProvider( 6826): in addTimaSignatureService
D/TimaKeyStoreProvider( 6826): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6826): Added TimaKesytore provider
W/AwContents( 6767): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2400): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  tag : ACTIVITY_RESUME_BOOSTER@4
D/CustomFrequencyManagerService( 2400): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/ActivityManager( 2400): mDVFSHelper.release()
W/AwContents( 6767): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 6767): showStatusIcon on inactive InputConnection
D/dalvikvm( 6826): GC_CONCURRENT freed 3001K, 30% free 9570K/13668K, paused 5ms+2ms, total 34ms
D/dalvikvm( 6826): WAIT_FOR_CONCURRENT_GC blocked 24ms
I/SELinux ( 6847): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6847):  
I/ActivityManager( 2400): Killing 5850:com.sec.android.soagent/u0a38 (adj 15): empty #43
,I/SELinux ( 6847): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6847):  
I/SELinux ( 6847):  
,I/SELinux ( 6847): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6847): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6847): >>>>> Normal User
,E/dalvikvm( 6847): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 6847): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 6012): GC_CONCURRENT freed 154K, 5% free 27189K/28472K, paused 3ms+3ms, total 71ms
,D/dalvikvm( 6012): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/TimaKeyStoreProvider( 6847): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6847): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6847): Added TimaKesytore provider
,D/dalvikvm( 6847): GC_CONCURRENT freed 2999K, 30% free 9574K/13672K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 6847): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/JsMessageQueue( 6767): Set native->JS mode to OnlineEventsBridgeMode
,D/KidsPlatformStub( 6847): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6862):  
I/ActivityManager( 2400): Killing 6181:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,I/SELinux ( 6862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6862):  
I/SELinux ( 6862):  
,I/SELinux ( 6862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6862): >>>>> Normal User
,E/dalvikvm( 6862): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6862): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6862): Added TimaKesytore provider
,D/dalvikvm( 6767): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42258c18
,D/dalvikvm( 6862): GC_CONCURRENT freed 2986K, 30% free 9580K/13668K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6862): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 6767): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42258c18
D/jxcore_app_log( 6767): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030882648
D/JX-Cordova( 6767): jxcore cordova android initializing
,I/SELinux ( 6874): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6874):  
I/ActivityManager( 2400): Killing 5931:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty #43
,I/SELinux ( 6874): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6874):  
I/SELinux ( 6874):  
,I/SELinux ( 6874): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6874): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6874): >>>>> Normal User
,E/dalvikvm( 6874): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6874): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6874): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6874): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6874): Added TimaKesytore provider
,I/Icing   ( 3158): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,D/dalvikvm( 6874): GC_CONCURRENT freed 3007K, 31% free 9567K/13672K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 6874): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/UMC:Core( 6874): onCreate(): 
,D/dalvikvm( 6767): GC_CONCURRENT freed 1272K, 18% free 11360K/13728K, paused 2ms+2ms, total 30ms
D/dalvikvm( 6767): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 6767): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/Icing   ( 3158): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/USER_AGENT( 6874): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/[SAMSUNG SMARCART NATIVE]( 6874): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6874): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/TZ_CCM_C_GetFunctionList: ( 6874): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6874): FINISHED: initialize rv:0
,D/CustomFrequencyManagerService( 2400): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 6874): GC_CONCURRENT freed 1869K, 22% free 10770K/13736K, paused 5ms+4ms, total 38ms
,D/dalvikvm( 6874): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/UMC:SecurityUtils( 6874): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6874): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6874): New Flow
,I/        ( 2400): CCM JNI: In ccm_register_for_default_cert
I/        ( 2400): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2400): &ctx = 0x7bd2b618
,I/TLC_TZ_CCM: ( 2400): creating new ccm context...
I/TLC_TZ_CCM: ( 2400): initializing ccm context...
I/TLC_TZ_CCM: ( 2400): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2400): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2400): input max_sendmsg_size = 19420
,I/TZ: client_server_communication( 2400): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2400): root = 0, root_len = 1
I/TZ: client_server_communication( 2400): process = ffffffff000000000000000000000012, process_strlen = 32
D/TimaService( 2400): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2400): TIMA: in getTimaVersion
I/TZ: client_server_communication( 2400): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2400): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2400): Client_Server_Open was called
I/TZ: client_server_communication( 2400): IClientServer::IClientServer()
I/TZ: client_server_communication( 2400): BpClientServer::BpClientServer()
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
,I/TZ: mc_tlc_communication( 2510): tlc_open() succeeded
,I/TZ: client_server_communication( 2400): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2400): ctx = 0x7ba749f0, comm = 0x895e5fd0, sendmsg = 0x895e82b8, recvmsg = 0x895eceb8
I/TZ_init: ( 2400): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
D/dalvikvm( 6767): GC_CONCURRENT freed 2019K, 18% free 14930K/18056K, paused 1ms+3ms, total 46ms
,D/dalvikvm( 6767): WAIT_FOR_CONCURRENT_GC blocked 38ms
,W/PluginManager( 6767): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 38ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 6767): WAIT_FOR_CONCURRENT_GC blocked 39ms
E/Parcel  ( 2400): nm 19456
E/TZ_init: ( 2400): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2400): trustlet initialization failed
,I/TZ_init: ( 2400): TZ_init_START...
,I/TZ_init: ( 2400): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TZ_init: ( 2400): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2400): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2400): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: ( 2400): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2400): TZ_CCM_register_default_TLC_END: DB file size to update is 0
,I/TLC_TZ_CCM: register for default cert: ( 2400): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: ( 2400): Exercising TZ_CCM_C_Finalize_TLC
,I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2400): nm 19456
I/TZ: client_server_communication( 2400): Client_Server_Close was called
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2510): tlc_close() was called
,I/TZ: mc_tlc_communication( 2510): Closing the session
I/TZ: mc_tlc_communication( 2510): Free WSM
,I/TZ: mc_tlc_communication( 2510): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2510): tlc_close() succeeded
,I/TZ: client_server_communication( 2400): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6874): TIMA service call for password change success!!
,D/UMC:AdminManager( 6874): init - start
,D/UMC:AdminManager( 6874): loadAdmins
,D/UMC:AdminManager( 6874): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6874): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6874): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6874): init - end
,V/UMC:AlarmHandler( 6874): Enter loadList
,D/EnterpriseDeviceManagerService( 2400): Creating context as user 0
,D/SPPApp  ( 6874): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6874): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6888): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6888):  
I/ActivityManager( 2400): Killing 6197:com.sec.android.app.clockpackage/u0a88 (adj 15): empty #43
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 6888): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6888):  
I/SELinux ( 6888):  
,I/SELinux ( 6888): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6888): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6888): >>>>> Normal User
,E/dalvikvm( 6888): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6888): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6888): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6888): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6888): Added TimaKesytore provider
,D/dalvikvm( 6888): GC_CONCURRENT freed 2993K, 30% free 9567K/13664K, paused 3ms+3ms, total 36ms
,D/dalvikvm( 6888): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/ApplicationPromenada( 6888): Application OnCreate start
,D/ApplicationPromenada( 6888): Application OnCreate po on Create
D/CrashReporter( 6888): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42264428
D/CrashReporter( 6888): Swaping uncaught exception handler
,D/ApplicationPromenada( 6888): Application OnCreate App Loader start
,D/ApplicationPromenada( 6888): Application OnCreate App Loader finish
,D/p2.ApplicationLoader( 6888): ############################## cached apps: 
,V/WebViewChromium( 6888): Binding Chromium to the background looper Looper (main, tid 1) {42267258}
,I/chromium( 6888): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6888): Initializing chromium process, renderers=0
,D/libEGL  ( 6888): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6888): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6888): loaded /system/lib/egl/libGLESv2_mali.so
,I/PowerManagerService( 2400): [PWL] Off : 75s ago
I/Mali    ( 6888): Mali API Version : 401
W/chromium( 6888): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Mali    ( 6888): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6888): Application OnCreate Finish
,I/ActivityManager( 2400): Killing 6217:com.sec.esdk.elm/u0a98 (adj 15): empty #43
,D/PackageBroadcastService( 3158): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3158): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 6767): GC_FOR_ALLOC freed 5275K, 29% free 16177K/22780K, paused 45ms, total 48ms
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3158): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3158): Submit a task: k
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3158): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3158): Processing package: com.test.thalitest
,D/GassUtils( 3158): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3158): Found info for package com.test.thalitest in db.
,D/Finsky  ( 3885): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 6888): GC_CONCURRENT freed 1780K, 22% free 10813K/13692K, paused 3ms+3ms, total 30ms
,D/dalvikvm( 6767): GC_CONCURRENT freed 6664K, 31% free 17666K/25428K, paused 3ms+10ms, total 72ms
,D/dalvikvm( 6888): GC_CONCURRENT freed 2364K, 25% free 10426K/13888K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 6767): GC_FOR_ALLOC freed 1502K, 32% free 17341K/25428K, paused 41ms, total 43ms
,I/dalvikvm-heap( 6767): Grow heap (frag case) to 21.544MB for 3713210-byte allocation
,I/Icing   ( 3158): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/dalvikvm( 6767): GC_FOR_ALLOC freed 2425K, 37% free 18542K/29056K, paused 41ms, total 41ms
,W/ResourceType( 6888): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6888): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6888): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6888): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6888): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6888): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6888): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6888): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6888): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6888): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6888): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6888): 	at java.lang.Thread.run(Thread.java:841)
,I/Icing   ( 3158): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,W/jxcore-log( 6767): Initializing JXcore engine
,W/jxcore-log( 6767): JXcore engine is ready
,W/jxcore-log( 6767): Starting JXcore engine
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,W/jxcore-log( 6767): Platform android
W/jxcore-log( 6767): 
,W/jxcore-log( 6767): Process ARCH arm
W/jxcore-log( 6767): 
,D/dalvikvm( 6888): GC_CONCURRENT freed 1995K, 25% free 10445K/13888K, paused 3ms+15ms, total 58ms
,D/p2.ApplicationLoader( 6888): Process time: 3050
,D/p2.ApplicationLoader( 6888): ##############################  apps after loading: 
,D/dalvikvm( 6888): GC_CONCURRENT freed 2273K, 28% free 10097K/13888K, paused 4ms+2ms, total 44ms
,I/jxcore-log( 6767): JXcore Cordova bridge is ready!
I/jxcore-log( 6767): 
,W/jxcore-log( 6767): JXcore engine is started
,I/chromium( 6767): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 72716 latestRequest time : 1450437990500 current time : 1450438063216
,I/VacuumService( 2734): Vacuum at: now=1450438063396 tag=VacuumService
,I/jxcore-log( 6767): Toggling radios to true
I/jxcore-log( 6767): 
,D/BluetoothAdapter( 6767): enable(): BT is already enabled..!
,I/WifiManager( 6767): packageName : com.test.thalitest
I/WifiManager( 6767): setWifiEnabled : true
,I/WifiService( 2400): setWifiEnabled: true pid=6767, uid=10562
,W/ActivityManager( 2400): Permission Denial: getCurrentUser() from pid=6767, uid=10562 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2400): Failed getting userId using ActivityManagerNative
W/WifiService( 2400): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6767, uid=10562 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2400): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2400): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2400): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2400): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2400): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2400): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2400): disconnect: pid=6767, uid=10562
I/jxcore-log( 6767): Radios toggled
I/jxcore-log( 6767): 
I/wpa_supplicant( 3977): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6767): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 6767): 
,I/jxcore-log( 6767): Perf Test app loaded loaded
I/jxcore-log( 6767): 
,I/wpa_supplicant( 3977): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 6767): check test folder
I/jxcore-log( 6767): 
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
I/jxcore-log( 6767): found test : ./testFindPeers.js
I/jxcore-log( 6767): 
I/wpa_supplicant( 3977): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3977): First Scan Start
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3977): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 2400): interfaceStatusChanged wlan0, true
W/Settings( 2400): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2400): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2400): InactiveState{ what=143375 }
D/WifiP2pService( 2400): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
D/ConnectivityService( 2400): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2400): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3977): Skip scan - already scanning
E/ConnectivityService( 2400): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2400): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2400): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2400): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2400): InactiveState{ what=143375 }
D/WifiP2pService( 2400): P2pEnabledState{ what=143375 }
,I/SELinux ( 6936): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6936):  
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/ConnectivityService( 2400): Attempting to switch to mobile
,I/jxcore-log( 6767): found test : ./testSendData.js
I/jxcore-log( 6767): 
D/ConnectivityService( 2400): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SELinux ( 6936): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6936):  
I/SELinux ( 6936):  
I/SELinux ( 6936): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6936): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6936): >>>>> Normal User
E/dalvikvm( 6936): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
E/SELinux ( 6936): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/WifiStateMachine( 2400): Error! unhandled message{ when=-87ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2400): Error! unhandled message{ when=-87ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2400): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2400): route cmd failed: 
W/NetworkManagementService( 2400): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2400): '
W/NetworkManagementService( 2400): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2400): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2400): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2400): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2400): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2400): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2400): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2400): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2400): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2400): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2400): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
D/TimaKeyStoreProvider( 6936): in addTimaSignatureService
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 370, Delta = 20
D/NetUtils( 2400): android_net_utils_resetConnections in env=0x75058660 clazz=0x62800001 iface=wlan0 mask=0x3
D/ConnectivityService( 2400): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 6936): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6936): Added TimaKesytore provider
,V/NativeCrypto( 2847): Read error: ssl=0x7c5e55f0: I/O error during system call, Connection timed out
,E/SPPClientService( 5611): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7c5e55f0: I/O error during system call, Broken pipe
,E/SPPClientService( 5611): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5611): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,I/chromium( 6767): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
V/NetworkStats( 2400): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService( 2400): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 6936): GC_CONCURRENT freed 2990K, 30% free 9580K/13672K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 6936): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 6936): Inside WakeupProvider
,I/System.out( 6936): Inside onCreate() of WakeupTriggerProvide
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,I/VlingoApplication( 6936): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6936): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6936): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/dalvikvm( 2400): GC_EXPLICIT freed 25233K, 71% free 25621K/88068K, paused 12ms+21ms, total 322ms
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
E/SPPClientService( 5611): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5611): [b] ResponseMap empty
V/NetworkStats( 2400): updateIfacesLocked()
V/NetworkStats( 2400): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
V/NetworkStats( 2400): performPollLocked() took 31ms
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NearbySettings( 4750): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4750): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4750): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4750): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 6936): initQueue()
I/ActivityManager( 2400): Killing 5389:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,D/NearbySettings( 4750): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4750): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4750): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4750): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2400): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2400): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2400): updateDataUsageMap
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,D/CaptivePortalTracker( 2400): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2400): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PCWCLIENTTRACE_PushUtil( 6668): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6668): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6668): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6668): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6668): noConnectivity : true
,I/DBG_DM  ( 4787): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2400): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 6966): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6966):  
,I/SELinux ( 6966): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6966):  
I/SELinux ( 6966):  
,I/SELinux ( 6966): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6966): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6966): >>>>> Normal User
,E/dalvikvm( 6966): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6966): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6966): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6966): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6966): Added TimaKesytore provider
,D/dalvikvm( 6966): GC_CONCURRENT freed 3011K, 31% free 9558K/13672K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 6966): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/wpa_supplicant( 3977): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3977): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
D/Tethering( 2400): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3977): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/ActivityManager( 2400): Killing 6245:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): Associated with C0.AA.48
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3977): freq(2412) increment count 2
,I/wpa_supplicant( 3977): meet head of list.
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3977): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3977): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2400): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2400): interfaceStatusChanged wlan0, true
,D/WifiNative( 2400): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6980): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6980):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9503K/10648K, paused 3ms+3ms, total 31ms
,I/SELinux ( 6980): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6980):  
I/SELinux ( 6980):  
,I/SELinux ( 6980): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6980): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6980): >>>>> Normal User
,E/dalvikvm( 6980): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 6980): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/WifiP2pService( 2400): InactiveState{ what=143375 }
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 2ms+3ms, total 24ms
,D/WifiP2pService( 2400): P2pEnabledState{ what=143375 }
D/TimaKeyStoreProvider( 6980): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6980): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6980): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 3ms+3ms, total 25ms
,D/dalvikvm( 6980): GC_CONCURRENT freed 2998K, 30% free 9573K/13668K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 6980): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/ActivityManager( 2400): Killing 6314:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/SELinux ( 6992): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6992):  
,I/SELinux ( 6992): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6992):  
I/SELinux ( 6992):  
,I/SELinux ( 6992): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6992): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6992): >>>>> Normal User
,E/dalvikvm( 6992): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6992): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6992): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6992): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6992): Added TimaKesytore provider
,I/dhcpcd  ( 6996): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6996): bssid match
,D/dalvikvm( 6992): GC_CONCURRENT freed 3007K, 31% free 9559K/13668K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 6992): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/KLMS-2.3.201 : ( 6992): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 6992): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450438065999
,I/KLMS-2.3.201 : ( 6992): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2400): Killing 6369:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7011): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7011):  
,I/SELinux ( 7011): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7011):  
I/SELinux ( 7011):  
,I/SELinux ( 7011): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7011): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7011): >>>>> Normal User
,E/dalvikvm( 7011): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7011): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7011): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7011): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7011): Added TimaKesytore provider
,D/dalvikvm( 7011): GC_CONCURRENT freed 3001K, 31% free 9570K/13672K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7011): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/SO_AGENT( 7011): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7011): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5880): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5880): [BDLM] already registered in spp
I/SA      ( 5880): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5880): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5880): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5880): [OR] == isSIMCardReady false ==
I/SA      ( 5880): [SCU] == networkStateCheck == false
,I/SA      ( 5880): [OR] onReceive END
I/ActivityManager( 2400): Killing 6381:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7023): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7023):  
,I/SELinux ( 7023): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7023):  
I/SELinux ( 7023):  
,I/SELinux ( 7023): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7023): >>>>> Normal User
,E/dalvikvm( 7023): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7023): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/libgps  ( 2400): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2400): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2400): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/TimaKeyStoreProvider( 7023): in addTimaSignatureService
,D/libgps  ( 2400): agps_ril_update_network_availability: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7023): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7023): Added TimaKesytore provider
,D/dalvikvm( 7023): GC_CONCURRENT freed 2998K, 30% free 9571K/13668K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7023): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/sCloudBackupApp( 7023): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7023): Other Intent
I/ActivityManager( 2400): Killing 6404:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PackageManager( 2400): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SELinux ( 7036): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7036):  
,I/SELinux ( 7036): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7036):  
I/SELinux ( 7036):  
,I/SELinux ( 7036): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7036): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7036): >>>>> Normal User
E/dalvikvm( 7036): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
E/SELinux ( 7036): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7036): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7036): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7036): Added TimaKesytore provider
,D/dalvikvm( 7036): GC_CONCURRENT freed 3002K, 30% free 9571K/13672K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7036): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7036): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7036): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5413): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7036): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5413): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7036): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5413): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2400): Killing 6461:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/Headlines( 5947): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5947): getCountryCode(): countryCode = PL
D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5947): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5947): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5947): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7048): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7048):  
,I/SELinux ( 7048): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7048):  
I/SELinux ( 7048):  
,I/SELinux ( 7048): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7048): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7048): >>>>> Normal User
,E/dalvikvm( 7048): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7048): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7048): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7048): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7048): Added TimaKesytore provider
,D/dalvikvm( 7048): GC_CONCURRENT freed 3006K, 31% free 9565K/13668K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7048): WAIT_FOR_CONCURRENT_GC blocked 18ms
,V/WebViewChromium( 7048): Binding Chromium to the background looper Looper (main, tid 1) {42264190}
,I/chromium( 7048): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7048): Initializing chromium process, renderers=0
,W/chromium( 7048): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7048): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7048): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7048): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7048): Mali API Version : 401
,I/Mali    ( 7048): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7048): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 7048): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7048): Starting up...
,I/iu.Environment( 6012): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 6012): SYNC; picasa accounts
,D/WifiP2pService( 2400): InactiveState{ what=143375 }
,D/WifiP2pService( 2400): P2pEnabledState{ what=143375 }
,I/ActivityManager( 2400): Killing 5664:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/WifiStateMachine( 2400): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.UploadsManager( 6012): num queued entries: 0
,I/iu.UploadsManager( 6012): num updated entries: 0
D/libgps  ( 2400): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2400): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2400): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/WifiStateMachine( 2400): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2400): CaptivePortalCheckState enter
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/iu.SyncManager( 6012): NEXT; no task
,I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2400): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2400): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2400): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/QuickConnect[1.1][2] ( 5214): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/WifiTrafficPoller( 2400): evaluateTrafficStatsPolling
I/QuickConnect[1.1][2] ( 5214): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5214): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422728e0
D/ConnectivityService( 2400): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2400): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2400): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,I/SELinux ( 7108): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7108):  
,D/ConnectivityService( 2400): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,W/ActivityManager( 2400): Failed to clear dns cache for: com.sec.android.widgetapp.activeapplicationwidget
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,I/SELinux ( 7108): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7108):  
I/SELinux ( 7108):  
I/SELinux ( 7108): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7108): >>>>> Normal User
E/dalvikvm( 7108): >>>>> com.android.email [ userId:0 | appId:10157 ]
V/RouteController( 1915): RTNETLINK answers: No such file or directory
,E/SELinux ( 7108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7108): in addTimaSignatureService
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7108): Cannot add TimaSignature Service, License check Failed
V/NetworkStats( 2400): updateIfacesLocked()
,V/NetworkStats( 2400): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
D/ActivityThread( 7108): Added TimaKesytore provider
D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
V/NetworkStats( 2400): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
V/NetworkStats( 2400): performPollLocked() took 19ms
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2400): currentTimeMillis() cache hit
,D/dalvikvm( 7108): GC_CONCURRENT freed 2985K, 30% free 9582K/13664K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7108): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,I/SELinux ( 7141): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7141):  
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
I/SELinux ( 7141): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7141):  
I/SELinux ( 7141):  
,I/SELinux ( 7141): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7141): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7141): >>>>> Normal User
,E/dalvikvm( 7141): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,E/SELinux ( 7141): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/ActivityManager( 2400): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 2400): Killing 6350:com.sec.phone/1001 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7141): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7141): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7141): Added TimaKesytore provider
,I/ActivityManager( 2400): Killing 4927:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty #43
,I/SELinux ( 7154): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7154):  
,I/SELinux ( 7154): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7154):  
I/SELinux ( 7154):  
,I/SELinux ( 7154): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7154): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7154): >>>>> Normal User
,E/dalvikvm( 7154): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7154): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 7141): GC_CONCURRENT freed 2989K, 30% free 9576K/13668K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7141): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/TimaKeyStoreProvider( 7154): in addTimaSignatureService
,D/BadgeProvider( 7141): onCreate
,D/BadgeProvider( 7141): DatabaseHelper
,D/TimaKeyStoreProvider( 7154): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7154): Added TimaKesytore provider
,D/BadgeProvider( 7141): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2774): reloadBadges entered.
,D/BadgeProvider( 7141): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7141): sendNotify, [notify] : null
D/BadgeProvider( 7141): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7141): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7141): update, [UpdateCount] : 1
,D/dalvikvm( 7154): GC_CONCURRENT freed 2993K, 30% free 9577K/13672K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7154): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Tethering( 2400): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2400): MasterInitialState.processMessage what=3
,D/hcjo    ( 6033): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6033): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6033): exit::IDLE
,D/InitializeManagerStateMachine( 6033): entry::NETWORK_CHECK
,D/CaptivePortalTracker( 2400): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/InitializeManagerStateMachine( 6033): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6033): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6033): entry::CHECK_COUNTRY_INFO
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
D/InitializeManagerStateMachine( 6033): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6033): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6033): entry::SUCCESS
D/hcjo    ( 6033): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/DBG_DM  ( 4787): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/hcjo    ( 6033): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6033): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6033): exit::SUCCESS
,D/InitializeManagerStateMachine( 6033): entry::IDLE
,E/SPPClientService( 5611): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5611): [SystemStateMoniter] Current Time : 153519
,E/SPPClientService( 5611): [SystemStateMoniter] No Connect : true
,D/libgps  ( 2400): agps_ril_update_network_state: Waiting for IPC connection...
,E/SPPClientService( 5611): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4750): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4750): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4750): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2400): Killing 6517:com.sec.knox.bridge/1000 (adj 15): empty #43
,E/SPPClientService( 5611): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5611): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4750): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4750): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5611): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 4750): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4750): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4750): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4750): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5611): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5611): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/PowerManagerService( 2400): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2400
,D/NearbySettings( 4750): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4750): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5611): [a] [ConnectionManager] Connection is already disconnected.
,I/PCWCLIENTTRACE_PushUtil( 6668): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6668): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6668): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6668): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5611): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 6992): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 6992): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450438068408
,I/KLMS-2.3.201 : ( 6992): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7011): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3468): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7011): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
D/PackageManager( 2400): [MSG] SEND_PENDING_BROADCAST
D/PackageManager( 2400): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@469a0e30, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/SELinux ( 7178): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7178):  
,I/SELinux ( 7178): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7178):  
I/SELinux ( 7178):  
,I/SELinux ( 7178): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7178): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7178): >>>>> Normal User
,E/dalvikvm( 7178): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7178): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/GallerySearchProvider( 3598): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/InputReader( 2400): Reconfiguring input devices.  changes=0x00000010
,D/TimaKeyStoreProvider( 7178): in addTimaSignatureService
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "sms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SA      ( 5880): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5880): [BDLM] already registered in spp
,I/SA      ( 5880): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5880): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/TimaKeyStoreProvider( 7178): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7178): Added TimaKesytore provider
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "smsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SA      ( 5880): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5880): [OR] == isSIMCardReady false ==
,I/SA      ( 5880): [SCU] == networkStateCheck == true
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SA      ( 5880): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5880): isChinaCountryCode : false
,I/SA      ( 5880): [OR] == networkStateCheck true ==
,I/SA      ( 5880): [OR] GetMyCountryZoneTask
,I/SA      ( 5880): [OR] onReceive END
,I/SA      ( 5880): [SRS] prepareGetMyCountryZone
,I/SA      ( 5880): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5880): [SSP] query invoked
,D/RegisteredServicesCache( 2756): empty dynamic service
,I/HarmonyEASService( 2400): Updating for all 1
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "mmsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7191): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7191):  
,D/dalvikvm( 7178): GC_CONCURRENT freed 2990K, 30% free 9581K/13668K, paused 8ms+1ms, total 54ms
,D/dalvikvm( 7178): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "sms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SA      ( 5880): [TPMU] GetMccFromDB : null
,I/SA      ( 5880): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5880): [TPM] isNoProxy(default) : true
,I/SA      ( 5880): [RC New] Execute method=[GET] start
,I/SELinux ( 7191): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7191):  
I/SELinux ( 7191):  
,I/SELinux ( 7191): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7191): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7191): >>>>> Normal User
,E/dalvikvm( 7191): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7191): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/System.out( 6980): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "smsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "mms"
,D/TimaKeyStoreProvider( 7191): in addTimaSignatureService
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7191): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7191): Added TimaKesytore provider
,I/System.out( 6980): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 6980): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2400):   Scheme: "mmsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7023): Other Intent
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7036): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/dalvikvm( 7191): GC_FOR_ALLOC freed 3023K, 31% free 9550K/13672K, paused 22ms, total 23ms
,D/Headlines( 5947): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5947): getCountryCode(): countryCode = PL
,W/WifiP2pStateTracker( 2400): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2400): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2400):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2400): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2400): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 7191): GC_CONCURRENT freed 233K, 15% free 9561K/11168K, paused 14ms+1ms, total 40ms
,D/dalvikvm( 7191): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5947): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5947): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5947): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5947): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 6012): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6012): num queued entries: 0
,D/QuickConnect[1.1][2] ( 5214): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/iu.UploadsManager( 6012): num updated entries: 0
,I/QuickConnect[1.1][2] ( 5214): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5214): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422728e0
,D/libgps  ( 2400): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2400): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2400): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2400): agps_ril_update_network_availability: Waiting for IPC connection...
,V/KVNProvider( 7191): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
V/KVNProvider( 7191): getFindoCursor query string : 
,D/RCPManagerService( 2400): exchangeData() failure , invalid userId
,I/iu.SyncManager( 6012): NEXT; no task
,V/KVNProvider( 7191): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 6033): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6033): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6033): exit::IDLE
,D/InitializeManagerStateMachine( 6033): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6033): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6033): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6033): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6033): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6033): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6033): entry::SUCCESS
,D/hcjo    ( 6033): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6033): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6033): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6033): exit::SUCCESS
D/InitializeManagerStateMachine( 6033): entry::IDLE
I/System.out( 6980): AsyncTask #1 calls detatch()
I/jxcore-log( 6767): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6767): 
W/System.err( 6980): com.sec.android.fota.osp.http.RestClientException
W/System.err( 6980): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 6980): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6980): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6980): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 6980): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6980): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6980): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6980): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6980): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 6980): Caused by: java.lang.NullPointerException
W/System.err( 6980): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 6980): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6980): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6980): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 6980): 	... 8 more
E/SPPClientService( 5611): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 5611): [SystemStateMoniter] Current Time : 154745
E/SPPClientService( 5611): [SystemStateMoniter] No Connect : false
I/ActivityManager( 2400): Killing 6420:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
D/dalvikvm( 5611): GC_CONCURRENT freed 1971K, 24% free 10435K/13652K, paused 9ms+3ms, total 51ms
W/ApplicationsProvider( 2976): Could not fetch usage stats
W/ApplicationsProvider( 2976): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2976): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2976): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2976): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2976): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2976): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 2400): GC_EXPLICIT freed 2831K, 71% free 25589K/88068K, paused 9ms+16ms, total 221ms
I/Icing.InternalIcingCorporaProvider( 6502): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
I/SELinux ( 7214): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7214):  
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9503K/10648K, paused 2ms+3ms, total 30ms
I/SELinux ( 7214): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7214):  
I/SELinux ( 7214):  
I/SELinux ( 7214): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7214): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7214): >>>>> Normal User
E/dalvikvm( 7214): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10073 ]
E/SELinux ( 7214): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SA      ( 5880): [RC New] [v2liruge] api execute + 822
I/SA      ( 5880): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 2ms+4ms, total 35ms
I/System.out( 5880): AsyncTask #2 calls detatch()
D/TimaKeyStoreProvider( 7214): in addTimaSignatureService
I/SA      ( 5880): [TPMU] getNetworkMcc : 
D/TimaKeyStoreProvider( 7214): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7214): Added TimaKesytore provider
I/Icing.InternalIcingCorporaProvider( 6502): UpdateCorporaTask done [took 105 ms] updated apps [took 104 ms] 
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 3ms+5ms, total 39ms
I/SA      ( 5880): [SCU] saveMccToPreferece Start
I/SA      ( 5880): [SCU] RegionMCC : 260
I/SA      ( 5880): [SSP] query invoked
I/SA      ( 5880): [TPMU] GetMccFromDB : null
I/SA      ( 5880): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5880): [SCU] saveMccToPreferece End
I/SA      ( 5880): [RC New] executeRequest [v2liruge] end. 883
I/SA      ( 5880): [RC New] Execute end
I/SA      ( 5880): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5880): [OR] GetMyCountryZoneTask Success
D/dalvikvm( 7214): GC_CONCURRENT freed 3015K, 31% free 9550K/13668K, paused 3ms+2ms, total 29ms
D/dalvikvm( 7214): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/FileShare-Server( 7214): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
I/SELinux ( 7226): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7226):  
I/ActivityManager( 2400): Killing 6062:com.android.calendar/u0a144 (adj 15): empty #43
I/SELinux ( 7226): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7226):  
I/SELinux ( 7226):  
I/SELinux ( 7226): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7226): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7226): >>>>> Normal User
E/dalvikvm( 7226): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
E/SELinux ( 7226): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7226): in addTimaSignatureService
D/TimaKeyStoreProvider( 7226): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7226): Added TimaKesytore provider
D/dalvikvm( 7226): GC_CONCURRENT freed 3003K, 30% free 9570K/13672K, paused 3ms+2ms, total 27ms
D/dalvikvm( 7226): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/BezelQuickConnect( 5226): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
D/BezelQuickConnect( 5226): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
D/PackageBroadcastService( 3158): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
I/ActivityManager( 2400): Killing 6232:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
D/libgps  ( 2400): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2400): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2400): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SPPClientService( 5611): [b] __InitReply__
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/WifiStateMachine( 2400): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Icing   ( 3158): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3158): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/ActivityManager( 2400): Killing 6267:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11),
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2400): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2400) eventTime = 157185
,D/PowerManagerService( 2400): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2400 (0x0)
,D/PowerManagerService( 2400): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2400, ws=WorkSource{1000}) (elapsedTime=3510)
,I/GAV2    ( 7048): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6668): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6668): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6668): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6668): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6668): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6668): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6668): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6668): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6668): [ensureRegistration] - No Samsung account
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 360, Delta = -10
,D/dalvikvm( 3885): GC_CONCURRENT freed 8048K, 36% free 16271K/25416K, paused 12ms+7ms, total 142ms
,D/dalvikvm( 3885): WAIT_FOR_CONCURRENT_GC blocked 119ms
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/Finsky  ( 3885): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3885): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PreloadUpdateManagerStateMachine( 6033): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6033): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6033): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/CaptivePortalTracker( 2400): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2400): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2400): Checking http://216.58.209.78/generate_204
,D/hcjo    ( 6033): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6033): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6033): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6033): entry::IDLE
,D/CaptivePortalTracker( 2400): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2400): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2400): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2400): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2400): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 6033): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6033): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6033): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6033): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6033): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6033): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6033): entry::IDLE
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2400): waitForAlarm result :8
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 11376 latestRequest time : 1450438069137 current time : 1450438080513
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 5
,I/ActivityManager( 2400): Waited long enough for: ServiceRecord{4539acf8 u0 com.sec.spp.push/.PushClientService}
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 340, Delta = -20
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 105s ago
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = -10
,D/AmoledAdjustTimer( 2400): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ClearcutLoggerApiImpl( 2847): disconnect managed GoogleApiClient
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 6
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2400): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 58359 latestRequest time : 1450438069137 current time : 1450438127496
,I/SELinux ( 7587): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7587):  
,I/SELinux ( 7587): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7587):  
I/SELinux ( 7587):  
,I/SELinux ( 7587): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7587): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7587): >>>>> Normal User
,E/dalvikvm( 7587): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 7587): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 7587): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7587): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7587): Added TimaKesytore provider
,D/dalvikvm( 7587): GC_CONCURRENT freed 3001K, 30% free 9570K/13672K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7587): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/SPPClientService( 7587): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7587): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7587): PushLog.txt file is not deleted.
D/SPPClientService( 7587): PushLog.txt file is not deleted.
,D/SPPClientService( 7587): ============PushLog. stop!
,E/SPPClientService( 5611): [b] __PingReply__
,I/ActivityManager( 2400): Killing 6612:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2400): waitForAlarm result :8
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 71378 latestRequest time : 1450438069137 current time : 1450438140515
,E/Watchdog( 2400): !@Sync 7
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2400): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2400): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 101393 latestRequest time : 1450438069137 current time : 1450438170530
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): stay LED for fully charged
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 8
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2400): waitForAlarm result :8
,D/Headlines( 5947): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5947): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5947): Breath 131395 latestRequest time : 1450438069137 current time : 1450438200532
,D/Headlines( 5947): stop 
,D/Headlines( 5947): Breath.onDestroy : 
,I/ActivityManager( 2400): Killing 6522:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/Watchdog( 2400): !@Sync 9
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2400): initializing...
,I/TLC_TIMA_PKM_initialize( 2400): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2400): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2400): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2400): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2400): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2400): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2400): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2400): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2400): device_id = 0x0
,I/TZ: mc_tlc_communication( 2400): tlc_open() was called
,I/TZ: mc_tlc_communication( 2400): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2400): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2400): Opening the session
,I/TZ: mc_tlc_communication( 2400): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2400): Trustlet response is completed
,E/Watchdog( 2400): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2400): [PWL] Off : 275s ago
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 11
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8229): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8229):  
,I/SELinux ( 8229): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8229):  
I/SELinux ( 8229):  
,I/SELinux ( 8229): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8229): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8229): >>>>> Normal User
,E/dalvikvm( 8229): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8229): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8229): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8229): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8229): Added TimaKesytore provider
,D/dalvikvm( 8229): GC_CONCURRENT freed 2998K, 31% free 9566K/13668K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 8229): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/ActivityManager( 2400): Killing 6643:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/jxcore-log( 6767): Connected to the server!
I/jxcore-log( 6767): 
,I/chromium( 6767): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6767): --- start :testFindPeers.js---
I/jxcore-log( 6767): 
,I/jxcore-log( 6767): testFindPeers created [object Object]
I/jxcore-log( 6767): 
,I/jxcore-log( 6767): serverPort is 8876
I/jxcore-log( 6767): 
,I/dalvikvm( 6767): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6767): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 6767): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 6767): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 6767): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6767): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 6767): Shutting down VM
,W/dalvikvm( 6767): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6767): FATAL EXCEPTION: main
E/AndroidRuntime( 6767): Process: com.test.thalitest, PID: 6767
E/AndroidRuntime( 6767): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 6767): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 6767): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 6767): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 6767): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 6767): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 6767): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 6767): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 6767): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 6767): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 6767): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 6767): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6767): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6767): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 6767): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 6767): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 6767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 6767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 6767): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2400):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2400): Killing 6655:com.android.musicfx/u0a24 (adj 15): empty #43
,D/CrashAnrDetector( 2400): processName: com.test.thalitest
,D/CrashAnrDetector( 2400): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 6767): Sending signal. PID: 6767 SIG: 9
D/CustomFrequencyManagerService( 2400): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
W/ActivityManager( 2400): mDVFSHelper.acquire()
,I/DBG_DM  ( 4787): [3.19.140541][Line:408][onResume] 
,I/ActivityManager( 2400): Process com.test.thalitest (pid 6767) (adj 9) has died.
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4787): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
I/WindowState( 2400): WIN DEATH: Window{44c7d050 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/DBG_DM  ( 4787): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4787): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4787): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4787): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4787): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4787): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2400): sendNotification(2) - 4
,I/DBG_DM  ( 4787): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4787): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4787): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4787): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4787): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4787): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4787): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4787): setTransGradationMode to true
D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4787): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2400): semi p:4787,o:t
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2400): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2400): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2400): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2400): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2400): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2400): Got RemoteException sending setActive(false) notification to pid 6767 uid 10562
,D/CustomFrequencyManagerService( 2400): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2400): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2400): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CustomFrequencyManagerService( 2400): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2400  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 12
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 2400): GC_CONCURRENT freed 4247K, 72% free 25307K/88068K, paused 17ms+21ms, total 253ms
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 13
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 14
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): stay LED for fully charged
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2400): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 15
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2400): !@Sync 16
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2400): [PWL] Off : 455s ago
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2580): GC_CONCURRENT freed 15728K, 34% free 33862K/50684K, paused 9ms+9ms, total 93ms
,E/Watchdog( 2400): !@Sync 17
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 18
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 19
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9041
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9043
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9044
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9046
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9048
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9049
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9051
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9053
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9054
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9055
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9056
,W/ProcessCpuTracker( 2400): Skipping unknown process pid 9058
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2400): !@Sync 20
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2400): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 21
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 600s ago
,V/AlarmManager( 2400): waitForAlarm result :4
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2400): LightSensor setDelay = 200000000
,D/LightsService( 2400): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
D/Sensors ( 2400): LightSensor enableSensor = 1
D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3158): Aggregate from 1450436773376 (log), 1450436773376 (data)
,D/dalvikvm( 3158): GC_CONCURRENT freed 2159K, 21% free 12537K/15784K, paused 24ms+8ms, total 127ms
,D/Sensors ( 2400): LightSensor enable = 0
,D/Sensors ( 2400): LightSensor enableSensor = 0
,D/SensorManager( 2400): unregisterListener ::   
D/LightsService( 2400): [SvcLED]  onSensorChanged::light value = 5
D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5707): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5707): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2400): !@Sync 22
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2400): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2400): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2400): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 23
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 24
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2883K, 30% free 9726K/13708K, paused 21ms+3ms, total 105ms
,E/Watchdog( 2400): !@Sync 25
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 26
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2400): GC_CONCURRENT freed 4137K, 72% free 25064K/88068K, paused 19ms+20ms, total 251ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 27
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 28
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 29
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2400): !@Sync 30
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 31
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 32
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 33
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 34
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 35
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 36
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/BatteryService( 2400): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2400): waitForAlarm result :4
,V/AlarmManager( 2400): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5611): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/SPPClientService( 5611): [b] __PingReply__
,I/PowerManagerService( 2400): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 37
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2400): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 38
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 39
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
E/Watchdog( 2400): !@Sync 40
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2400): GC_CONCURRENT freed 3904K, 72% free 25071K/88068K, paused 48ms+16ms, total 319ms
,D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 179ms
,E/Watchdog( 2400): !@Sync 41
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,I/SensorManagerA( 2400): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2400): LightSensor setDelay = 200000000
,D/Sensors ( 2400): LightSensor setSensorDelay = 200000000
,D/LightsService( 2400): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2400): Light sensor flush: not enabled 0
D/Sensors ( 2400): LightSensor enable = 1
D/Sensors ( 2400): LightSensor enableSensor = 1
,D/SensorManager( 2400): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2400): LightSensor enable = 0
,D/Sensors ( 2400): LightSensor enableSensor = 0
D/LightsService( 2400): [SvcLED]  onSensorChanged::light value = 8
,D/SensorManager( 2400): unregisterListener ::   
D/LightsService( 2400): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 42
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2400): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2400): <AppSync3 Whitelist>
,V/AlarmManager( 2400): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 43
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1265s ago
,E/Watchdog( 2400): !@Sync 44
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 45
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2400): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 46
,D/BatteryService( 2400): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2400): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2400): stay LED for fully charged
,D/UiModeManager( 2400): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 47
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 48
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2050K, 30% free 9724K/13708K, paused 3ms+5ms, total 45ms
D/dalvikvm( 4091): WAIT_FOR_CONCURRENT_GC blocked 12ms
,E/Watchdog( 2400): !@Sync 49
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2400): !@Sync 50
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 51
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 52
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 53
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 54
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2400): !@Sync 55
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 56
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2400): GC_CONCURRENT freed 3910K, 72% free 24952K/88068K, paused 24ms+18ms, total 255ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 57
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 58
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 59
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2400): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2400): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2400): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2400): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2400): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2400): !@Sync 60
,I/PowerManagerService( 2400): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2400): Prepared write state in 41ms
,I/ProcessStatsService( 2400): Pruning old procstats: /data/system/procstats/state-2015-12-17-14-21-00.bin
,I/ProcessStatsService( 2400): Prepared write state in 25ms
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 61
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 62
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2400): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2400): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2400): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 63
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2400): !@Sync 64
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2400): [PWL] Off : 1890s ago
,V/AlarmManager( 2400): waitForAlarm result :8
,V/AlarmManager( 2400): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2400): Killing 7191:com.sec.android.app.voicenote/1000 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 7178:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 5880:com.osp.app.signin/u0a44 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 6697:com.policydm/1000 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 7011:com.sec.android.soagent/u0a38 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 6936:com.vlingo.midas/u0a34 (adj 15): empty for 1811s
I/ActivityManager( 2400): Killing 6992:com.samsung.klmsagent/u0a18 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 6980:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 5822:com.sec.android.diagmonagent/1000 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 6966:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1811s
I/ActivityManager( 2400): Killing 6668:com.sec.pcw.device/1000 (adj 15): empty for 1811s
,I/ActivityManager( 2400): Killing 7141:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1812s
,I/ActivityManager( 2400): Killing 6478:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1820s
,I/ActivityManager( 2400): Killing 6888:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1821s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2400): Killing 6874:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1822s
,I/ActivityManager( 2400): Killing 6862:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1822s
,I/ActivityManager( 2400): Killing 6847:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1822s
,I/ActivityManager( 2400): Killing 6826:com.samsung.helphub/1000 (adj 15): empty for 1823s
I/ActivityManager( 2400): Killing 6791:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1823s
,I/ActivityManager( 2400): Killing 6779:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1823s
,I/ActivityManager( 2400): Killing 6751:com.sec.android.service.cm/u0a82 (adj 15): empty for 1823s
I/ActivityManager( 2400): Killing 6434:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1824s
,I/ActivityManager( 2400): Killing 5774:com.android.mms/u0a49 (adj 15): empty for 1824s
,I/ActivityManager( 2400): Killing 6713:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1824s
,I/ActivityManager( 2400): Killing 6076:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1824s
,I/ActivityManager( 2400): Killing 6681:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1825s
,D/CountryDetector( 2400): No listener is left
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2400): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2400): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
D/AndroidRuntime(12177): 
D/AndroidRuntime(12177): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12177): CheckJNI is OFF
D/AndroidRuntime(12177): setted country_code = Poland
D/AndroidRuntime(12177): setted countryiso_code = PL
D/AndroidRuntime(12177): setted sales_code = PLS
D/AndroidRuntime(12177): readGMSProperty: start
D/AndroidRuntime(12177): readGMSProperty: already setted!!
D/AndroidRuntime(12177): readGMSProperty: end
D/AndroidRuntime(12177): addProductProperty: start
D/dalvikvm(12177): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12177): Added shared lib libjavacore.so 0x0
D/dalvikvm(12177): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12177): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12177): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(12177): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12177): failed to load memtrack module: -2
D/dalvikvm(12177): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(12177): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2400): START PACKAGE DELETE: observer{1113383656}
D/PackageManager( 2400): pkg{<packageName>}
D/PackageManager( 2400): user{0}
D/PackageManager( 2400): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2400): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2400): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 2400): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 2400): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2400): !@killApplicatoin: 10562, uninstall pkg
W/PackageSettings( 2400): Skipping PackageSetting{422dc1b8 com.example.hello/10551} due to missing metadata
D/PackageManager( 2400): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10562, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2400): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10562, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6502): GC_EXPLICIT freed 2481K, 28% free 9884K/13668K, paused 10ms+6ms, total 74ms
E/SamsungIME( 3008): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5214): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
I/SELinux (12205): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12205):  
D/dalvikvm( 2976): GC_EXPLICIT freed 1465K, 27% free 10033K/13664K, paused 12ms+7ms, total 152ms
I/SELinux (12205): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12205):  
I/SELinux (12205):  
I/SELinux (12205): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12205): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12205): >>>>> Normal User
E/dalvikvm(12205): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12205): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/Watchdog( 2400): !@Sync 65
D/dalvikvm( 3158): GC_EXPLICIT freed 326K, 22% free 12463K/15784K, paused 15ms+12ms, total 238ms
I/InputReader( 2400): Reconfiguring input devices.  changes=0x00000010
D/RegisteredServicesCache( 2756): empty dynamic service
D/TimaKeyStoreProvider(12205): in addTimaSignatureService
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "sms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12205): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12205): Added TimaKesytore provider
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "smsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2400): GC_EXPLICIT freed 3788K, 72% free 25050K/88068K, paused 12ms+23ms, total 341ms
D/dalvikvm( 2400): WAIT_FOR_CONCURRENT_GC blocked 310ms
D/dalvikvm( 2774): GC_CONCURRENT freed 8900K, 39% free 18401K/30104K, paused 9ms+6ms, total 68ms
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mmsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2400): PackageReceiver onReceive()
I/HarmonyEASService( 2400): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "sms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12205): GC_CONCURRENT freed 3001K, 31% free 9566K/13668K, paused 4ms+1ms, total 74ms
D/dalvikvm(12205): WAIT_FOR_CONCURRENT_GC blocked 42ms
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "smsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(12205): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(12205): ELMEngine.ELMEngine( context ).
D/elm:14132(12205): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mmsto"
D/EnterpriseDeviceManagerService( 2400): Package has changed for user 0
D/dalvikvm( 2756): GC_CONCURRENT freed 2336K, 26% free 10255K/13684K, paused 12ms+5ms, total 110ms
D/elm:14132(12205): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(12205): ElmAgentService : onCreate()
D/elm:14132(12205): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12205): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12205): MDMBridge.getInstance()
D/elm:14132(12205): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12220): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12220):  
D/elm:14132(12205): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(12205): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(12205): ElmAgentService : onDestroy().
I/ActivityManager( 2400): Killing 7023:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1814s
I/SELinux (12220): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12220):  
I/SELinux (12220):  
I/SELinux (12220): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12220): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12220): >>>>> Normal User
E/dalvikvm(12220): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12220): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12220): in addTimaSignatureService
D/TimaKeyStoreProvider(12220): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12220): Added TimaKesytore provider
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12220): GC_CONCURRENT freed 3006K, 31% free 9562K/13668K, paused 3ms+2ms, total 23ms
D/dalvikvm(12220): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/BackupManagerService( 2400): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2400): removePackageParticipantsLocked: uid=10562 #1
D/dalvikvm( 2400): GC_EXPLICIT freed 1102K, 72% free 25050K/88068K, paused 20ms+46ms, total 546ms
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12235): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12235):  
I/ActivityManager( 2400): Killing 7036:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1814s
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12235): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12235):  
I/SELinux (12235):  
I/SELinux (12235): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12235): >>>>> Normal User
E/dalvikvm(12235): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (12235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager( 2400): delete sourFile : 
D/TimaKeyStoreProvider(12235): in addTimaSignatureService
D/TimaKeyStoreProvider(12235): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12235): Added TimaKesytore provider
W/ApplicationsProvider( 2976): Could not fetch usage stats
W/ApplicationsProvider( 2976): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2976): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2976): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2976): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2976): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2976): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2976): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PackageManager( 2400): delete native library directory: 
D/PackageManager( 2400): return delete result to caller: 1113383656
D/AndroidRuntime(12177): Shutting down VM
D/PackageManager( 2400): returnCode: 1
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12177): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12235): GC_CONCURRENT freed 3009K, 31% free 9561K/13668K, paused 3ms+2ms, total 24ms
D/dalvikvm(12235): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "sms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2400): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "smsto"
I/CrashAnrDetector( 2400): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2400): clearDefaults: com.test.thalitest
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mms"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2400):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2400):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2400):   Scheme: "mmsto"
I/PackageManager( 2400): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12249): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12249):  
I/ActivityManager( 2400): Killing 7048:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1815s
I/SELinux (12249): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12249):  
I/SELinux (12249):  
I/SELinux (12249): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12249): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12249): >>>>> Normal User
E/dalvikvm(12249): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (12249): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12249): in addTimaSignatureService
D/TimaKeyStoreProvider(12249): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12249): Added TimaKesytore provider
D/dalvikvm(12249): GC_CONCURRENT freed 2989K, 30% free 9576K/13668K, paused 5ms+2ms, total 34ms
D/dalvikvm(12249): WAIT_FOR_CONCURRENT_GC blocked 27ms
I/SELinux (12264): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12264):  
I/SELinux (12264): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12264):  
I/SELinux (12264):  
I/SELinux (12264): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12264): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12264): >>>>> Normal User
E/dalvikvm(12264): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
I/ActivityManager( 2400): Killing 7108:com.android.email/u0a157 (adj 15): empty for 1815s
E/SELinux (12264): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12264): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(12264): in addTimaSignatureService
D/TimaKeyStoreProvider(12264): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12264): Added TimaKesytore provider
D/dalvikvm(12264): GC_CONCURRENT freed 3008K, 31% free 9557K/13664K, paused 3ms+2ms, total 25ms
D/dalvikvm(12264): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(12264): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12264): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12264): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12264): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12264): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12264): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12264): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12264): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12264): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12264): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12264): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12264): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12264): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12264): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12264): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12264): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12264): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12264): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12264): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12264): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12264): Shutting down VM
W/dalvikvm(12264): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12264): FATAL EXCEPTION: main
E/AndroidRuntime(12264): Process: com.sec.pcw.device, PID: 12264
E/AndroidRuntime(12264): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12264): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12264): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12264): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12264): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12264): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12264): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12264): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12264): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12264): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12264): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12264): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12264): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12264): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12264): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12264): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12264): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12264): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12264): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12264): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12264): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12264): 	... 12 more
E/DropBoxManagerService( 2400): Can't write: system_app_crash
E/DropBoxManagerService( 2400): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2400): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2400): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2400): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2400): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2400): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2400): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2400): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2400): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2400): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2400): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2400): 	... 5 more
I/SELinux (12278): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12278):  
I/Process (12264): Sending signal. PID: 12264 SIG: 9
I/ActivityManager( 2400): Process com.sec.pcw.device (pid 12264) (adj 0) has died.
I/SELinux (12278): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12278):  
I/SELinux (12278):  
I/SELinux (12278): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12278): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12278): >>>>> Normal User
E/dalvikvm(12278): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12278): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12278): in addTimaSignatureService
D/TimaKeyStoreProvider(12278): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12278): Added TimaKesytore provider
D/dalvikvm(12278): GC_CONCURRENT freed 2997K, 30% free 9570K/13664K, paused 3ms+2ms, total 24ms
D/dalvikvm(12278): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/System.err(12278): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12278): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12278): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12278): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12278): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12278): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12278): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12278): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12278): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12278): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12278): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12278): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12278): 	at libcore.io.Posix.open(Native Method)
W/System.err(12278): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12278): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12278): 	... 21 more
D/GalaxyFinderApplication(12278): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12278): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12292): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12292):  
I/ActivityManager( 2400): Killing 7154:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1816s
I/SELinux (12292): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12292):  
I/SELinux (12292):  
I/SELinux (12292): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12292): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12292): >>>>> Normal User
E/dalvikvm(12292): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12292): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12292): in addTimaSignatureService
D/TimaKeyStoreProvider(12292): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12292): Added TimaKesytore provider
D/dalvikvm(12292): GC_CONCURRENT freed 3011K, 31% free 9558K/13668K, paused 3ms+2ms, total 25ms
D/dalvikvm(12292): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(12292): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12292): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12292): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12292): ContentProvider is not null
W/ResourceType(12292): No package identifier when getting value for resource number 0x00000000
I/System.out(12292): resource Id::2131361807
E/SQLiteDatabase(12292): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12292): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12292): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12292): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12292): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12292): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12292): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12292): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12292): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12292): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12292): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12292): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12292): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12292): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12292): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12292): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12292): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12292): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12292): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12292): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12292): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12292): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12292): Shutting down VM
W/dalvikvm(12292): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12292): FATAL EXCEPTION: main
E/AndroidRuntime(12292): Process: com.sec.android.app.shealth, PID: 12292
E/AndroidRuntime(12292): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12292): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12292): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12292): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12292): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12292): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12292): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12292): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12292): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12292): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12292): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12292): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12292): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12292): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12292): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12292): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12292): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12292): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12292): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12292): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(12292): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(12292): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(12292): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(12292): 	... 10 more
E/DropBoxManagerService( 2400): Can't write: system_app_crash
E/DropBoxManagerService( 2400): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2400): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2400): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2400): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2400): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2400): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2400): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2400): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2400): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2400): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2400): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2400): 	... 5 more
I/SELinux (12312): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12312):  
I/Process (12292): Sending signal. PID: 12292 SIG: 9
I/ActivityManager( 2400): Process com.sec.android.app.shealth (pid 12292) (adj 0) has died.
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9503K/10648K, paused 2ms+4ms, total 36ms
I/SELinux (12312): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12312):  
I/SELinux (12312):  
I/SELinux (12312): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/SamsungIME( 3008): onTrimMeomory Level = 5
E/SELinux (12312): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(12312): >>>>> Normal User
E/dalvikvm(12312): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 3ms+3ms, total 32ms
E/SELinux (12312): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/HeadlinesChannelApplication( 5947): HeadlinesChannelApplication.onTrimMemory(). level : 60
W/GeoLookout( 3004): at (DisasterAlertApplication.java:67) [onTrimMemory()]
I/EsApplication( 6012): Trimming memory (onTrimMemory 40)
E/rsC++   ( 2774): RS Message thread exiting.
E/OpenGLRenderer( 2774): SFEffectCache:clear(), mSize = 0
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9503K/10648K, paused 3ms+4ms, total 31ms
D/Launcher( 2774): onTrimMemory. Level: 80
W/ManagedEGLContext( 2774): doTerminate failed: EGL count is 2 but managed count is 1
D/TimaKeyStoreProvider(12312): in addTimaSignatureService
D/TimaKeyStoreProvider(12312): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12312): Added TimaKesytore provider
D/dalvikvm(12312): GC_CONCURRENT freed 2998K, 30% free 9577K/13672K, paused 3ms+2ms, total 24ms
D/dalvikvm(12312): WAIT_FOR_CONCURRENT_GC blocked 20ms
E/SQLiteDatabase(12312): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase(12312): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12312): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12312): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12312): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12312): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase(12312): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12312): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12312): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12312): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12312): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12312): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12312): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12312): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12312): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12312): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12312): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12312): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12312): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12312): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12312): Shutting down VM
W/dalvikvm(12312): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12312): FATAL EXCEPTION: main
E/AndroidRuntime(12312): Process: com.samsung.android.sdk.samsunglink, PID: 12312
E/AndroidRuntime(12312): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12312): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12312): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12312): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12312): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12312): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12312): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12312): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12312): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12312): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12312): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12312): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12312): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12312): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12312): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12312): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12312): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12312): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime(12312): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12312): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12312): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12312): 	... 12 more

```
