#### Test 625481246b04bc0_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,--------- beginning of system
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4931 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4727:com.google.android.gm/u0a63 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_4727/cgroup.procs: No such file or directory
D/AndroidRuntime( 4926): 
D/AndroidRuntime( 4926): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4926): CheckJNI is OFF
I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4980 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/AndroidRuntime( 4926): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5001 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4778:com.android.providers.calendar/u0a5 (adj 15): empty #7
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_4778/cgroup.procs: No such file or directory
D/AndroidRuntime( 4926): Shutting down VM
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5018 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 2602): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2602): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2602): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2602): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2602): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2602): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2602): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2602): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2602): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2602): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2602): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2602): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ResourcesManager( 4847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  885): Activity reported stop, but no longer stopping: ActivityRecord{1e8db864 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
V/JNIHelp ( 4847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ContactLocale( 5001): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5044 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4876:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 24.539ms
,W/System  ( 4847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4847): Installed default security provider GmsCore_OpenSSL
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.191ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 315us total 20.820ms
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_4876/cgroup.procs: No such file or directory
,W/asset   ( 5044): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5044): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5044): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5044): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/WebViewFactory( 5018): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5018): Time to load native libraries: 3 ms (timestamps 6274-6277)
I/LibraryLoader( 5018): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5018): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
I/LibraryLoader( 5018): Expected native library version number "",actual native library version number ""
,I/chromium( 5018): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5018): Initializing chromium process, singleProcess=true
,W/art     ( 5018): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5018): ApplicationContext is null in ApplicationStatus
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 4931): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1967): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PkgBroadcastIntentOp( 1967): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5078 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:38000 mC
,D/WearableController( 1967): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1967): updateResources: need to parse f{com.google.android.gms}
,W/chromium( 5018): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5018): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5018): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5018): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5018): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5018): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5018): Local Branch: 
I/Adreno-EGL( 5018): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5018): Local Patches: NONE
I/Adreno-EGL( 5018): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/ResourcesManager( 5078): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SFPerfTracer(  278):      triggers: (rate: 14:452) (compose: 0:1) (post: 0:1) (render: 0:2) (11:930 frames) (12:1007)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb727cda8): 0:11)* (DimLayer (0xb724f240): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7253ac8): 0:33)- (StatusBar (0xb7272070): 0:129) (NavigationBar (0xb7274460): 0:30) (com.android.systemui.ImageWallpaper (0xb7276850): 0:32)* (Starting com.motorola.ccc.ota (0xb7298cb0): 0:36)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb729b830): 1:47)* (Starting com.test.thalitest (0xb7253ac8): 12:23) 
,D/BluetoothManagerService(  885): Message: 20
,D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15f76827:true
,I/UpdateIcingCorporaServi( 4931): UpdateCorporaTask done [took 282 ms] updated apps [took 282 ms] 
,I/art     ( 1749): Explicit concurrent mark sweep GC freed 39104(2MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 13MB/22MB, paused 2.525ms total 112.693ms
,W/art     ( 5018): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5018): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5018): CordovaWebView is running on device made by: motorola
,W/art     ( 5018): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5018): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5124 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OpenGLRenderer( 5018): Render dirty regions requested: true
,D/Atlas   ( 5018): Validating map...
,W/chromium( 5018): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  885): Killing 4901:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_4901/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 4816:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_4816/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 5018): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5018): Enabling debug mode 0
,I/Keyboard.Facilitator( 1420): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1246
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +1s246ms
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5147 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Adreno-ES20( 5018): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5018): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/ResourcesManager( 5147): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/BindingManager( 5018): Cannot call determinedVisibility() - never saw a connection for the pid: 5018
,I/CalendarProvider2( 5147): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,D/Finsky  ( 5124): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/JsMessageQueue( 5018): Set native->JS mode to OnlineEventsBridgeMode
,D/Finsky  ( 5124): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5124): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5124): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  885): Explicit concurrent mark sweep GC freed 15553(772KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.614ms total 144.105ms
,D/Finsky  ( 5124): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5124): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5124): Skipping gmscore version check
,I/Icing   ( 1967): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  885): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5199 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4980:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (21:272 vsyncs) (23:1063)
,E/Adreno-ES20( 5018): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5018): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_4980/cgroup.procs: No such file or directory
,D/Finsky  ( 5124): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/jxcore_app_log( 5018): JniHelper::setJavaVM(0xb8649310), pthread_self() = -1197454616
,D/Finsky  ( 5124): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e23af9f added. We now have 1 listener(s)
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5018): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5018): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5018): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5018): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdb174a added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5018): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  885): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5018): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5018): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 5018): Constructor: Bluetooth LE discovery mode is not supported
D/Icing   ( 1967): Loaded CLD2 Version V2.0 - 20141016
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ActivityThread( 5199): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 5199): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1967): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5227 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/chromium( 5018): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/CalendarProvider2( 5147): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5147): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/ActivityManager(  885): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5227): EasService.onCreate
,W/GAV2    ( 5199): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 5227): RestartPingTask
,I/Gmail   ( 5199): Observing account changes for notifications
,I/Exchange( 5227): RestartPingsTask did not start any pings.
I/Exchange( 5227): PSS stopIfIdle
I/Exchange( 5227): PSS has no active accounts; stopping service.
,I/ActivityManager(  885): Killing 5044:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_5044/cgroup.procs: No such file or directory
,I/Gmail   ( 5199): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 5227): onDestroy
,I/ActivityManager(  885): Killing 4931:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_4931/cgroup.procs: No such file or directory
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2602): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2602): time to show notification
,I/ActivityManager(  885): Killing 5001:android.process.acore/u0a7 (adj 15): empty #7
,E/SQLiteLog( 5199): (283) recovered 76 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5199): notifyAccountChanged
,I/Gmail   ( 5199): getAccountsCursor
,I/Gmail   ( 5199): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5199): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5199): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5199): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/BroadcastQueue(  885): Exception when sending broadcast to ComponentInfo{com.android.providers.contacts/com.android.providers.contacts.PackageIntentReceiver}
W/BroadcastQueue(  885): android.os.DeadObjectException
W/BroadcastQueue(  885): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  885): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  885): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:867)
W/BroadcastQueue(  885): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:263)
W/BroadcastQueue(  885): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:921)
W/BroadcastQueue(  885): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16280)
W/BroadcastQueue(  885): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:478)
W/BroadcastQueue(  885): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2514)
W/BroadcastQueue(  885): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_5001/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5266 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ActivityManager(  885): Spurious death for ProcessRecord{2a5abc18 5266:android.process.acore/u0a7}, curProc for 5001: null
,W/ResourcesManager( 1295): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivatableNotificationView( 1295):  oops Width=0 ActualHeight=128
,I/Gmail   ( 5199): getAccountsCursor
,I/ContactLocale( 5266): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5286 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5078:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_5078/cgroup.procs: No such file or directory
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5307 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5124:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_5124/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/asset   ( 5307): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5307): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5307): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5328 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 3194:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_3194/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5349 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/jxcore-log( 5018): Initializing JXcore engine
W/jxcore-log( 5018): JXcore engine is ready
,I/GservicesProvider( 5349): Gservices pushing to system: true; secure/global: true
,I/art     ( 1967): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,W/Thread-569( 5222): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5609]" dev="sockfs" ino=5609 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-569( 5222): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-569( 5222): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[5715]" dev="sockfs" ino=5715 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-569( 5222): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[21978]" dev="sockfs" ino=21978 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5018): Starting JXcore engine
,I/GoogleHttpClient( 5349): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5349): GMS http client unavailable, use old client
,D/PkgBroadcastIntentOp( 1967): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1967): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/UpdateIcingCorporaServi( 5328): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  885): Killing 5227:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/jxcore-log( 5018): Platform android
W/jxcore-log( 5018): 
,W/jxcore-log( 5018): Process ARCH arm
W/jxcore-log( 5018): 
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  885): failed to open /acct/uid_10060/pid_5227/cgroup.procs: No such file or directory
,I/art     (  885): Explicit concurrent mark sweep GC freed 12332(649KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.978ms total 126.164ms
,D/AsyncTaskServiceImpl( 1967): Submit a task: k
,D/k       ( 1967): Processing package: com.test.thalitest
,D/GassUtils( 1967): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1967): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1967): Using Auth Proxy for data requests.
W/BaseAppContext( 1967): Using Auth Proxy for data requests.
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5395 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.459ms
,W/BaseAppContext( 1967): Using Auth Proxy for data requests.
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 19.645ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.476ms
,W/BaseAppContext( 1967): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 5328): UpdateCorporaTask done [took 529 ms] updated apps [took 528 ms] 
,I/ActivityManager(  885): Killing 5199:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_5199/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {312f6f43, *alarm*:android.intent.action.TIME_TICK}
,W/BaseAppContext( 1967): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1967): cleanUpNonGplusAccounts done.
,I/SFPerfTracer(  278):      triggers: (rate: 14:453) (compose: 0:1) (post: 0:1) (render: 0:2) (31:1030 frames) (32:1120)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb727cda8): 0:14)* (DimLayer (0xb724f240): 0:6)* (StatusBar (0xb7272070): 32:165) (NavigationBar (0xb7274460): 0:30) (com.android.systemui.ImageWallpaper (0xb7276850): 0:32)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb729b830): 0:48)- (Starting com.test.thalitest (0xb7253ac8): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb72992b0): 0:60) 
,V/AlarmManager(  885): done {312f6f43, *alarm*:android.intent.action.TIME_TICK} [83ms]
,I/jxcore-log( 5018): JXcore Cordova bridge is ready!
I/jxcore-log( 5018): 
,W/jxcore-log( 5018): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5018): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5018): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5018): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5018): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5018): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2602): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2602): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2602): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2602): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5018): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1420): onFinishInput()
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,8167
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5223 (total)
,I/ActivityManager(  885): Killing 4847:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_4847/cgroup.procs: No such file or directory
,I/GAv4    ( 5395): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5395):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5395):   adb logcat -s GAv4
,W/GAv4    ( 5395): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5395): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5395): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5395): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/Icing   ( 1967): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/Icing   ( 1967): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/Icing   ( 1967): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/ContextImpl( 5395): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5395): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5395): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5433 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5147:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/Icing   ( 1967): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (49:370 vsyncs) (51:1172)
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_5147/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 5266:android.process.acore/u0a7 (adj 15): empty #7
,W/ResourcesManager( 5433): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5395): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_5266/cgroup.procs: No such file or directory
,W/System  ( 5395): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5395): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5458 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5481 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5286:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/ContactLocale( 5458): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_5286/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {7d27aee, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/ActivityManager(  885): Killing 5307:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_5307/cgroup.procs: No such file or directory
,D/Finsky  ( 5481): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5481): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5481): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5481): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5481): Skipping gmscore version check
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5526 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Finsky  ( 5481): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5481): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5481): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5481): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 5526): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Finsky  ( 5481): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Killing 5328:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_5328/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 5395:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5556 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_5395/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5573 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5556): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5556): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/Gmail   ( 5573): getAccountsCursor
D/ActivityThread( 5573): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5600 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 5573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  885): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5600): EasService.onCreate
,I/Exchange( 5600): RestartPingTask
,I/Gmail   ( 5573): Observing account changes for notifications
,I/Exchange( 5600): RestartPingsTask did not start any pings.
,I/Exchange( 5600): PSS stopIfIdle
,I/Exchange( 5600): PSS has no active accounts; stopping service.
,I/Gmail   ( 5573): getAccountsCursor
,I/Exchange( 5600): onDestroy
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Killing 5018:com.test.thalitest/u0a109 (adj 15): empty #7
,D/WifiService(  885): Client connection lost with reason: 4
,W/libprocessgroup(  885): failed to open /acct/uid_10109/pid_5018/cgroup.procs: No such file or directory
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Killing 5433:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/SQLiteLog( 5573): (283) recovered 77 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5573): notifyAccountChanged
,I/Gmail   ( 5573): getAccountsCursor
,I/Gmail   ( 5573): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5573): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5573): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5573): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_5433/cgroup.procs: No such file or directory
,I/art     (  885): Explicit concurrent mark sweep GC freed 13511(658KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.557ms total 120.222ms
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): done {7d27aee, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [1476ms]
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5556): (284) automatic index on view_events(_id)
,I/Gmail   ( 5573): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CalendarProvider2( 5556): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5556): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Killing 5458:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_5458/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task.xml
,D/Finsky  ( 5481): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  885): send {2d5ed6dc, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  885): send {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  885): done {2d5ed6dc, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [16ms]
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.66 rxSuccessRate=1.59 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=1458042364381 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=1458042364381 interval=20000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN bump interval =30000
I/wpa_supplicant( 1418): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  885): done {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN} [23ms]
,E/WifiStateMachine(  885): [1,458,042,364,387 ms] noteScanstart no scan source
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 15 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  492): NL - Read 56 bytes from update socket.
D/TCMD    (  492): NL - message type is RTM_NEWLINK
D/TCMD    (  492): Listening for incoming client connection request
,E/WifiStateMachine(  885): [1,458,042,364,920 ms] noteScanEnd no scan source,
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5481): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5481): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 5481): untagSocket(37) failed with errno -22
,D/Finsky  ( 5481): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  885): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5653 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5653): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5653): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5653): VM with version 2.1.0 has multidex support
I/MultiDex( 5653): install
I/MultiDex( 5653): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5653): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5653): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5653): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5653): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1749): callingUid 10016, callindPid: 1749
,E/MDM     ( 1749): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 5653): Reading stored module config
,D/LocationInitializer( 1967): Restart initialization of location
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:37000 mC
,I/qtaguid ( 5481): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5481): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5481): untagSocket(37) failed with errno -22
,D/CAR.SERVICE( 5653): Connecting to CarCallService...
,D/NativeLibraryUtils( 5653): Install completed successfully. count=14 extracted=0
,I/art     ( 5653): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5653): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5653): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5653): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5653): Creating a new PhoneAdapter instance
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5653): setListener: com.google.android.gms.car.dn@1dd60e23
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5653): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5653): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5653): Package validated; name: com.android.vending
,V/Finsky  ( 5481): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5481): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5481): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5481): untagSocket(37) failed with errno -22
,W/ActivityManager(  885): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5481): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5481): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5481): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  885): send {115b9eb3, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  885): done {115b9eb3, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [18ms]
,D/DeviceConnectionService( 1749): client connected with version: 8296000
,D/Finsky  ( 5481): [650] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5481): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5481): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): send {271c3988, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {271c3988, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [3ms]
,I/GAV2    ( 5573): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  885): Killing 5600:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10060/pid_5600/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{c98e463 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): send {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,D/CAR.SERVICE( 5653): mConnectedToCar = false, abort
,E/ActivityThread( 5653): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2781b4ab that was originally bound here
E/ActivityThread( 5653): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2781b4ab that was originally bound here
E/ActivityThread( 5653): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5653): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5653): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5653): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5653): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5653): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5653): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5653): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5653): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5653): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5653): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5653): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5653): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5653): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5653): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5653): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5653): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5653): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5653): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5653): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5653): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5653): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5653): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5653): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2305b52 that was originally bound here
E/ActivityThread( 5653): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2305b52 that was originally bound here
E/ActivityThread( 5653): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5653): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5653): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5653): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5653): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5653): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5653): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5653): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5653): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5653): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5653): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5653): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5653): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5653): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5653): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5653): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5653): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5653): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5653): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5653): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5653): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5653): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  885): Unbind failed: could not find connection for android.os.BinderProxy@38ff6634
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:36000 mC
,I/ActivityManager(  885): Killing 5573:com.google.android.gm/u0a63 (adj 15): empty #7
,I/ActivityManager(  885): Killing 5556:com.android.providers.calendar/u0a5 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_5573/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_5556/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): send {2d0049d2, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  885): send {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  885): done {2d0049d2, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [14ms]
,V/AlarmManager(  885): done {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN} [17ms]
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.78 rxSuccessRate=2.49 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=17118 interval=30000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  885): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
I/wpa_supplicant( 1418): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  885): [1,458,042,381,502 ms] noteScanstart no scan source
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  492): NL - Read 56 bytes from update socket.
D/TCMD    (  492): NL - message type is RTM_NEWLINK
D/TCMD    (  492): Listening for incoming client connection request
,E/WifiStateMachine(  885): [1,458,042,381,571 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,D/Finsky  ( 5481): [640] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5481): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:35000 mC
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=314, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311503, SEQNUM=4384, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-183, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:34000 mC
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): send {1046b1a0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): send {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): done {1046b1a0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [19ms]
,V/AlarmManager(  885): done {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN} [21ms]
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.03 rxSuccessRate=0.04 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=35158 interval=30000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN try full band scan age=35158 interval=30000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN bump interval =45000
I/wpa_supplicant( 1418): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  885): [1,458,042,399,548 ms] noteScanstart no scan source
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1749): Vacuum at: now=1458042399712 tag=VacuumService
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 17 
,D/TCMD    (  492): NL - Read 56 bytes from update socket.
D/TCMD    (  492): NL - message type is RTM_NEWLINK
D/TCMD    (  492): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  885): [1,458,042,399,972 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,V/AlarmManager(  885): send {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,E/ActivityThread( 1967): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  885): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 192834, reason: UserStart
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:34000 mC
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=304, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311357, SEQNUM=4390, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13221, POWER_SUPPLY_CHARGE_COUNTER=-234, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,E/BackupManagerService(  885): Timeout restoring application @pm@
W/BackupManagerService(  885): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1749): Restore processing aborted, no more packages
,E/BackupManagerService(  885): Failure getting next package name
E/BackupManagerService(  885): Duplicate finish
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  885): send {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN with age=17416 interval=45000 maxinterval=300000
E/WifiStateMachine(  885): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  885): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
I/wpa_supplicant( 1418): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  885): done {19bdd849, *alarm*:com.android.server.WifiManager.action.START_SCAN} [12ms]
,E/WifiStateMachine(  885): [1,458,042,416,964 ms] noteScanstart no scan source
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  492): NL - Read 56 bytes from update socket.
D/TCMD    (  492): NL - message type is RTM_NEWLINK
D/TCMD    (  492): Listening for incoming client connection request
,E/WifiStateMachine(  885): [1,458,042,417,031 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): send {312f6f43, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {312f6f43, *alarm*:android.intent.action.TIME_TICK} [33ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
,I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ConfigService( 1749): onCreate
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ConfigService( 1749): onDestroy
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:33000 mC
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,V/AlarmManager(  885): send {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PowerManagerService(  885): Nap time (uid 1000)...
I/PowerManagerService(  885): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  885): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  885): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  885): Build Date: 10/28/14 Tue
I/Adreno-EGL(  885): Local Branch: 
I/Adreno-EGL(  885): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  885): Local Patches: NONE
I/Adreno-EGL(  885): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  885): activate, handle: 1598182242, enabled: 0, index 2
D/        (  885): BstSensorExt: id=1598182242, en=0
,D/        (  885): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 222
,D/        (  885): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  885): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  885): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb715e550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  288): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8a7c820
I/rmt_storage(  288): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  288): wakelock acquired: 1, error no: 42
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1196964552)
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1196964552) wakelock released: 1, error no: 0
I/rmt_storage(  288): 
,I/rmt_storage(  288): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8a7c820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  885): Excessive delay in setPowerMode(): 342ms
,I/WindowManager(  885): AOD feature not enabled!
,I/PowerManagerService(  885): Sleeping (uid 1000)...
,I/SFPerfTracer(  278):       trigger: frame rate (-28.725%)	(42.765 fps)	(23.384 ms) 	(2 drops)	(15 frames)
,I/SFPerfTracer(  278):      triggers: (rate: 15:455) (compose: 0:1) (post: 0:1) (render: 0:2) (15:1089 frames) (16:1200)
D/SFPerfTracer(  278):        layers: (4:11) (FocusedStackFrame (0xb727cda8): 0:16)* (DimLayer (0xb724f240): 0:8)* (StatusBar (0xb7272070): 0:189) (NavigationBar (0xb7274460): 0:43) (com.android.systemui.ImageWallpaper (0xb7276850): 0:32)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb72992b0): 0:87)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7253ac8): 0:31) (ColorFade (0xb72992b0): 16:18) 
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WifiStateMachine(  885): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  293): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  293): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  293): platform_set_parameters: exit with code(0)
E/msm8974_platform(  293): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  293): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  293): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  885): do suspend false
,I/Keyboard.Facilitator( 1420): onFinishInput()
,D/        (  885): activate, handle: 1598182229, enabled: 0, index 0
E/        (  885): <BST> disable accel, orig state: 1
I/        (  885): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  293): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  293): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  293): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  293): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  293): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  885): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  885): do suspend true
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/art     (  885): Explicit concurrent mark sweep GC freed 60048(2MB) AllocSpace objects, 8(398KB) LOS objects, 33% free, 21MB/32MB, paused 1.452ms total 144.236ms
,V/AlarmManager(  885): send {33c248da, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  885): done {33c248da, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311492, SEQNUM=4398, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1009, POWER_SUPPLY_CHARGE_COUNTER=-288, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  885): send {2e87a10b, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {2e87a10b, *walarm*:com.google.android.intent.action.SEND_IDLE} [10ms]
,I/PhenotypeConfigurator( 1749): Scheduling Phenotype for one-off execution 10241 seconds from now (1458042464489)
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/PhenotypeFlagCommitter( 1749): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1749): Using platform SSLCertificateSocketFactory
,E/global frequency( 2602): no tags to log
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2602): Explicit concurrent mark sweep GC freed 24904(1417KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.245ms total 79.595ms
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1467): Explicit concurrent mark sweep GC freed 55578(3MB) AllocSpace objects, 35(1211KB) LOS objects, 40% free, 7MB/12MB, paused 719us total 44ms
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2602): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2602): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2602): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2602): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c4d813a)
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@373be1eb)
E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a16fb48)
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e091de1)
,E/DataBuffer( 1749): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e027706)
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1749): disconnect managed GoogleApiClient
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  885): send {496b3d7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  885): done {496b3d7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311700, SEQNUM=4402, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-301, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ConfigService( 1749): onCreate
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1749): onDestroy
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311588, SEQNUM=4404, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-308, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311281, SEQNUM=4405, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-355, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {312f6f43, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {312f6f43, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {312f6f43, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM} [19ms]
,V/AlarmManager(  885): done {312f6f43, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5808 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5808): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  885): Explicit concurrent mark sweep GC freed 20560(1027KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.565ms total 131.971ms
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5844 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 5526:com.motorola.context/u0a8 (adj 15): empty #7
,I/ContactLocale( 5844): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_5526/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 3109:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10049/pid_3109/cgroup.procs: No such file or directory
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM}
V/AlarmManager(  885): done {1fa0b507, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {312f6f43, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {271c3988, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {271c3988, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [26ms]
,V/AlarmManager(  885): done {312f6f43, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {312f6f43, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {1d1640c7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5880 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): done {312f6f43, *alarm*:android.intent.action.TIME_TICK} [86ms]
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 33.287ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 39.568ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.833ms
,I/GAv4    ( 5880): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5880):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5880):   adb logcat -s GAv4
,W/GAv4    ( 5880): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5880): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5880): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {1d1640c7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [262ms]
,I/ActivityManager(  885): Killing 5653:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_5653/cgroup.procs: No such file or directory
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311135, SEQNUM=4417, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-964, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2479): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5921): 
D/AndroidRuntime( 5921): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5921): CheckJNI is OFF
D/AndroidRuntime( 5921): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
W/PackageSettings(  885): Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
W/GeofencerStateMachine( 1749): Ignoring removeGeofence because network location is disabled.
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
I/art     ( 3035): Explicit concurrent mark sweep GC freed 10014(2MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 7MB/12MB, paused 901us total 50.688ms
I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
D/VoicemailCleanupService( 5844): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1420): createOrResetDecoder
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5952 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  885): Explicit concurrent mark sweep GC freed 20078(1502KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 21MB/32MB, paused 1.805ms total 173.451ms
I/art     (  885): WaitForGcToComplete blocked for 160.674ms for cause Explicit
I/art     ( 1967): Explicit concurrent mark sweep GC freed 2910(172KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/19MB, paused 982us total 96.864ms
I/art     ( 1576): Explicit concurrent mark sweep GC freed 2190(117KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 458us total 85.589ms
I/ConfigService( 1749): onCreate
W/asset   ( 5952): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5952): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5952): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5952): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): run()
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1420): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1420): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1420): run()
I/StatsUtilsManager( 1420): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1420): shouldRecordStats() = Too Soon
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5977 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  885): Explicit concurrent mark sweep GC freed 4027(202KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 2.200ms total 183.994ms
I/ActivityManager(  885): Killing 5481:com.android.vending/u0a32 (adj 15): empty #7
I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_5481/cgroup.procs: No such file or directory
D/AndroidRuntime( 5921): Shutting down VM
W/ContextImpl( 5977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5995 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  885): Killing 1967:com.google.android.gms/u0a16 (adj 15): empty #7
D/WifiService(  885): Client connection lost with reason: 4
D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d84d11c)
D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_1967/cgroup.procs: No such file or directory
W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  885): Start proc com.google.android.gms for service com.google.android.gms/.chimera.GmsIntentOperationService: pid=6014 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/ActivityManager(  885): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6036 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
W/ResourcesManager( 6014): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6014): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6014): VM with version 2.1.0 has multidex support
I/MultiDex( 6014): install
I/MultiDex( 6014): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  885): Killing 5349:com.google.process.gapps/u0a16 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_5349/cgroup.procs: No such file or directory
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
