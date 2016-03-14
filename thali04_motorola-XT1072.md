#### Test 625090943f585e4_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,D/Finsky  ( 4719): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 4719): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
--------- beginning of system
I/ActivityManager(  882): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4791 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  882): Killing 4647:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
I/ThermalEngine(  320): Sensor:xo_therm_pu2:38000 mC
W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_4647/cgroup.procs: No such file or directory
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4816 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 4576:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
I/Icing   ( 1954): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_4576/cgroup.procs: No such file or directory
W/asset   ( 4816): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 4816): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4816): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4816): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/Icing   ( 1954): Loaded CLD2 Version V2.0 - 20141016
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4841 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1954): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
I/ActivityManager(  882): Killing 4680:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 4811): 
D/AndroidRuntime( 4811): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4811): CheckJNI is OFF
W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_4680/cgroup.procs: No such file or directory
D/PkgBroadcastIntentOp( 1954): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/WearableController( 1954): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/AndroidRuntime( 4811): Calling main entry com.android.commands.am.Am
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 1954): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (172 us)
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4811): Shutting down VM
I/SFPerfTracer(  279):      triggers: (rate: 14:450) (compose: 0:1) (post: 0:1) (render: 0:2) (0:917 frames) (1:995)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb856bdb8): 0:10)* (DimLayer (0xb852cdd0): 0:3)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb85309a8): 0:33)- (StatusBar (0xb8518828): 0:162) (NavigationBar (0xb851c8c0): 0:30) (com.android.systemui.ImageWallpaper (0xb8550110): 0:8)* (Starting com.motorola.ccc.ota (0xb8567f68): 0:30)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8554c58): 0:28) 
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4876 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/AsyncTaskServiceImpl( 1954): Submit a task: k
,D/k       ( 1954): Processing package: com.test.thalitest
,I/UpdateIcingCorporaServi( 4841): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/GassUtils( 1954): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1954): Found info for package com.test.thalitest in db.
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4912 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/WebViewFactory( 4876): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4876): Time to load native libraries: 4 ms (timestamps 7593-7597)
I/LibraryLoader( 4876): Expected native library version number "",actual native library version number ""
,I/art     ( 1740): Explicit concurrent mark sweep GC freed 43438(2MB) AllocSpace objects, 34(544KB) LOS objects, 39% free, 13MB/22MB, paused 4.147ms total 121.407ms
,W/BaseAppContext( 1954): Using Auth Proxy for data requests.
W/BaseAppContext( 1954): Using Auth Proxy for data requests.
,W/BaseAppContext( 1954): Using Auth Proxy for data requests.
V/WebViewChromiumFactoryProvider( 4876): Binding Chromium to main looper Looper (main, tid 1) {25c44c98}
,I/LibraryLoader( 4876): Expected native library version number "",actual native library version number ""
I/chromium( 4876): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/BaseAppContext( 1954): Using Auth Proxy for data requests.
,I/BrowserStartupController( 4876): Initializing chromium process, singleProcess=true
W/art     ( 4876): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4876): ApplicationContext is null in ApplicationStatus
,W/BaseAppContext( 1954): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1954): cleanUpNonGplusAccounts done.
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4937 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4937): Created com.android.providers.calendar.CalendarAlarmManager@127b0e75(com.android.providers.calendar.CalendarProvider2@4afe0a)
,I/ActivityManager(  882): Killing 4719:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_4719/cgroup.procs: No such file or directory
,W/chromium( 4876): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4876): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4876): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4876): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4876): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4876): Local Branch: 
I/Adreno-EGL( 4876): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4876): Local Patches: NONE
I/Adreno-EGL( 4876): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d1517e2:true
,W/art     ( 4876): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4876): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4876): CordovaWebView is running on device made by: motorola
,W/art     ( 4876): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4876): Attempt to remove local handle scope entry from IRT, ignoring
,I/UpdateIcingCorporaServi( 4841): UpdateCorporaTask done [took 933 ms] updated apps [took 933 ms] 
,I/GAv4    ( 4912): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4912):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4912):   adb logcat -s GAv4
,W/GAv4    ( 4912): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/OpenGLRenderer( 4876): Render dirty regions requested: true
,W/GAv4    ( 4912): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4912): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Atlas   ( 4876): Validating map...
,W/chromium( 4876): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/AnalyticsTrackerProxyImpl( 4912): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (28:258 vsyncs) (30:1042)
,I/OpenGLRenderer( 4876): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4876): Enabling debug mode 0
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1412
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s412ms
,I/Icing   ( 1954): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,E/Adreno-ES20( 4876): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4876): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4912): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/Icing   ( 1954): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/BindingManager( 4876): Cannot call determinedVisibility() - never saw a connection for the pid: 4876
,W/ResourcesManager( 4912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4996 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 4768:com.motorola.context/u0a8 (adj 15): empty #7
,I/art     (  330): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 22.552ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.170ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.009ms
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_4768/cgroup.procs: No such file or directory
,I/CalendarProvider2( 4937): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4937): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  882): Killing 4621:android.process.acore/u0a7 (adj 15): empty #7
,D/JsMessageQueue( 4876): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 4996): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 4912): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_4621/cgroup.procs: No such file or directory
,W/System  ( 4912): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4912): Installed default security provider GmsCore_OpenSSL
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  882): Explicit concurrent mark sweep GC freed 17041(841KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 5.925ms total 164.209ms
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5022 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Adreno-ES20( 4876): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4876): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/Icing   ( 1954): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,D/jxcore_app_log( 4876): JniHelper::setJavaVM(0xb7d2a310), pthread_self() = -1207367824
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d3b8aa4 added. We now have 1 listener(s)
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5048 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4876): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4876): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4876): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4876): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e019dd3 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4876): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  882): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4876): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4876): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 4876): Constructor: Bluetooth LE discovery mode is not supported
,I/ActivityManager(  882): Killing 4791:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/ContactLocale( 5022): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 4816:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
I/chromium( 4876): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_4791/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_4816/cgroup.procs: No such file or directory
,I/Icing   ( 1954): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,D/Finsky  ( 5048): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5048): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5048): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5048): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5048): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5048): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5048): Skipping gmscore version check
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5092 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Finsky  ( 5048): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  882): Killing 4477:com.google.android.talk/u0a70 (adj 15): empty #7
,D/Finsky  ( 5048): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,W/ResourcesManager( 5092): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_4477/cgroup.procs: No such file or directory
,D/Finsky  ( 5048): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 4841:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_4841/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 4912:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_4912/cgroup.procs: No such file or directory
,D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 4876): Initializing JXcore engine
W/jxcore-log( 4876): JXcore engine is ready
,W/Thread-560( 5068): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5572]" dev="sockfs" ino=5572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-560( 5068): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-560( 5068): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9681]" dev="sockfs" ino=9681 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-560( 5068): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22093]" dev="sockfs" ino=22093 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4876): Starting JXcore engine
,W/jxcore-log( 4876): Platform android
W/jxcore-log( 4876): 
W/jxcore-log( 4876): Process ARCH arm
W/jxcore-log( 4876): 
,I/SFPerfTracer(  279):      triggers: (rate: 14:454) (compose: 0:1) (post: 0:1) (render: 0:2) (17:1012 frames) (18:1107)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb856bdb8): 0:15)* (DimLayer (0xb852cdd0): 0:6)* (StatusBar (0xb8518828): 0:179) (NavigationBar (0xb851c8c0): 0:43) (com.android.systemui.ImageWallpaper (0xb8550110): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8554c58): 0:54)- (Starting com.test.thalitest (0xb8567f68): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8557048): 18:55) 
,I/jxcore-log( 4876): JXcore Cordova bridge is ready!
I/jxcore-log( 4876): 
,W/jxcore-log( 4876): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4876): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4876): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 4876): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4876): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4876): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 4876): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/PluginManager( 4876): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2524): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2524): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2524): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2524): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2524): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2524): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2524): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2524): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 4876): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,11407
I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5086 (total)
,D/AndroidRuntime( 5121): 
D/AndroidRuntime( 5121): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5121): CheckJNI is OFF
,D/AndroidRuntime( 5121): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,I/ActivityManager(  882): Killing 4876:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,D/WifiService(  882): Client connection lost with reason: 4
,I/WindowState(  882): WIN DEATH: Window{25a0edb6 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/PackageSettings(  882): Skipping PackageSetting{12f2d593 com.example.hello/10568} due to missing metadata
,W/ActivityManager(  882): Spurious death for ProcessRecord{11480097 4876:com.test.thalitest/u0a109}, curProc for 4876: null
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,V/AlarmManager(  882): send {17a07284, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1740): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
I/art     ( 2939): Explicit concurrent mark sweep GC freed 10452(1653KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 712us total 66.125ms
,D/VoicemailCleanupService( 5022): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1417): createOrResetDecoder
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 2228(120KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 456us total 90.197ms
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5155 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1740): onCreate
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (48:359 vsyncs) (50:1159)
,W/asset   ( 5155): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5155): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5155): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5155): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
,I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5178 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  882): Killing 4937:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/art     (  882): Explicit concurrent mark sweep GC freed 25376(1786KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 5.083ms total 267.361ms
,D/AndroidRuntime( 5121): Shutting down VM
,W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_4937/cgroup.procs: No such file or directory
,W/ContextImpl( 5178): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  882): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5197 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,D/TaskPersister(  882): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  882): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5215 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 4996:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_4996/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 3094:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_3094/cgroup.procs: No such file or directory
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3693972d new=com.google.android.velvet.VelvetApplication@3693972d
,D/PkgBroadcastIntentOp( 1954): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1954): Clearing selected account for com.test.thalitest
,I/LocationSettingsChecker( 1954): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1740): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1740): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5245 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5269 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5289 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/GservicesProvider( 5269): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 5269): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 5269): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5269): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5269): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5269): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5269): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 5269): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 5269): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/SQLiteDatabase( 5269): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/SQLiteDatabase( 5269): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/SQLiteDatabase( 5269): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/SQLiteDatabase( 5269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/SQLiteDatabase( 5269): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 5269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/SQLiteDatabase( 5269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5269): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5269): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/SQLiteDatabase( 5269): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5269): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/SQLiteDatabase( 5269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
D/AndroidRuntime( 5269): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 5269): FATAL EXCEPTION: main
E/AndroidRuntime( 5269): Process: com.google.process.gapps, PID: 5269
E/AndroidRuntime( 5269): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5269): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5054)
E/AndroidRuntime( 5269): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/AndroidRuntime( 5269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/AndroidRuntime( 5269): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 5269): 	at android.app.Act,ivityThread$H.handleMessage(ActivityThread.java:1353)
E/AndroidRuntime( 5269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5269): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5269): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 5269): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5269): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 5269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 5269): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5269): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5269): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5269): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5269): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 5269): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 5269): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/AndroidRuntime( 5269): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/AndroidRuntime( 5269): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/AndroidRuntime( 5269): 	... 11 more
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5307 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SharedPreferencesImpl( 5215): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
E/AndroidRuntime( 5215): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5215): Process: com.google.android.googlequicksearchbox:search, PID: 5215
E/AndroidRuntime( 5215): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime( 5215): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime( 5215): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime( 5215): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5215): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5215): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5215): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5215): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5215): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 5215): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime( 5215): 	... 7 more
E/AndroidRuntime( 5215): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5215): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 5215): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5215): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5215): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5215): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 5215): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 5215): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5215): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 5215): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 5215): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 5215): 	... 9 more
E/AndroidRuntime( 5215): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5215): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 5215): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 5215): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 5215): 	... 11 more
,I/art     (  330): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.499ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 18.798ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.528ms
,I/GAv4    ( 5245): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5245):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5245):   adb logcat -s GAv4
,W/GAv4    ( 5245): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5245): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5245): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5245): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5245): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5245): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,W/AnalyticsTrackerProxyImpl( 5245): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30

```
