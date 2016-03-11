#### Test 62509094ffd3875_thali04_motorola-XT1072 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.gass from APK com.google.android.gms
V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 1945): Processing package: com.test.thalitest
D/GassUtils( 1945): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1945): Found info for package com.test.thalitest in db.
W/Finsky  ( 4418): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4418): [1] DailyHygiene.access$600: Logging device features
--------- beginning of system
V/AlarmManager(  885): send {32cb3151, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
D/Finsky  ( 4418): [1] DailyHygiene.reschedule: Scheduling new run in 880 minutes (failures=5)
,I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4772 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 4674): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/art     ( 1708): Explicit concurrent mark sweep GC freed 32307(1926KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 13MB/21MB, paused 974us total 86.469ms
D/DeviceConnectionService( 1708): client connected with version: 8296000
D/Finsky  ( 4418): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4418): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  885): Killing 4548:com.google.android.gm/u0a63 (adj 15): empty #7
I/ActivityManager(  885): Killing 4497:com.android.providers.calendar/u0a5 (adj 15): empty #8
W/libprocessgroup(  885): failed to open /acct/uid_10063/pid_4548/cgroup.procs: No such file or directory
W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_4497/cgroup.procs: No such file or directory
D/AndroidRuntime( 4770): 
D/AndroidRuntime( 4770): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4770): CheckJNI is OFF
I/UpdateIcingCorporaServi( 4674): UpdateCorporaTask done [took 418 ms] updated apps [took 418 ms] 
I/ActivityManager(  885): Killing 4652:android.process.acore/u0a7 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_4652/cgroup.procs: No such file or directory
I/GAv4    ( 4772): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4772):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4772):   adb logcat -s GAv4
W/GAv4    ( 4772): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/AndroidRuntime( 4770): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/GAv4    ( 4772): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4772): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4772): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
D/PermissionCache(  281): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (164 us)
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4770): Shutting down VM
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4821 uid=10577 gids={50577, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Icing   ( 1945): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4772): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 4772): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4772): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4848 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 4720:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Icing   ( 1945): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_4720/cgroup.procs: No such file or directory
,W/ResourcesManager( 4848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 4772): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WebViewFactory( 4821): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4821): Time to load native libraries: 2 ms (timestamps 6670-6672)
I/LibraryLoader( 4821): Expected native library version number "",actual native library version number ""
,W/System  ( 4772): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4772): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4821): Binding Chromium to main looper Looper (main, tid 1) {2dd47983}
,I/LibraryLoader( 4821): Expected native library version number "",actual native library version number ""
,I/SFPerfTracer(  281):      triggers: (rate: 15:510) (compose: 0:1) (post: 0:1) (render: 0:2) (7:923 frames) (8:991)
D/SFPerfTracer(  281):        layers: (5:12) (FocusedStackFrame (0xb8dd1270): 0:12)* (DimLayer (0xb8dc8738): 0:5) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8d3e1d0): 0:38)- (StatusBar (0xb8d42c40): 1:167) (NavigationBar (0xb8db0af8): 0:35) (com.android.systemui.ImageWallpaper (0xb8db6dc8): 0:6)* (Starting com.motorola.ccc.ota (0xb8dbd038): 0:29)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8de1158): 8:53) (Starting com.test.thalitest (0xb8dbd038): 8:12) 
,I/chromium( 4821): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4821): Initializing chromium process, singleProcess=true
,W/art     ( 4821): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4821): ApplicationContext is null in ApplicationStatus
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4874 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/chromium( 4821): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/Icing   ( 1945): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,W/chromium( 4821): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4821): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4821): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4821): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4821): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4821): Local Branch: 
I/Adreno-EGL( 4821): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4821): Local Patches: NONE
I/Adreno-EGL( 4821): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/Finsky  ( 4418): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,V/AlarmManager(  885): done {32cb3151, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [1624ms]
,D/Finsky  ( 4418): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 4418): [500] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@119b03a1:true
,D/BluetoothAdapter( 4821): 752560863: getState() :  mService = null. Returning STATE_OFF
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1945): Explicit concurrent mark sweep GC freed 58486(3MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 14MB/24MB, paused 3.395ms total 158.003ms
,I/ContactLocale( 4874): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/art     ( 4821): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  885): Explicit concurrent mark sweep GC freed 13656(659KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.579ms total 129.978ms
,W/AwContents( 4821): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  885): Killing 4693:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/SystemWebViewEngine( 4821): CordovaWebView is running on device made by: motorola
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_4693/cgroup.procs: No such file or directory
,W/art     ( 4821): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4821): Attempt to remove local handle scope entry from IRT, ignoring
,I/Icing   ( 1945): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,D/OpenGLRenderer( 4821): Render dirty regions requested: true
,D/Atlas   ( 4821): Validating map...
,W/chromium( 4821): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  885): Killing 4772:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_4772/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 4821): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4821): Enabling debug mode 0
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1346
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +1s346ms
,I/Keyboard.Facilitator( 1413): onFinishInput()
,E/Adreno-ES20( 4821): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4821): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4821): Cannot call determinedVisibility() - never saw a connection for the pid: 4821
,D/JsMessageQueue( 4821): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4932 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4932): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4932): Created com.android.providers.calendar.CalendarAlarmManager@2ef594(com.android.providers.calendar.CalendarProvider2@2749d83d)
,I/ActivityManager(  885): Killing 4848:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/Adreno-ES20( 4821): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4821): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_4848/cgroup.procs: No such file or directory
,D/jxcore_app_log( 4821): JniHelper::setJavaVM(0xb7e3f310), pthread_self() = -1206062816
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@135fe78c added. We now have 1 listener(s)
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4821): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4821): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4821): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4821): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1739addb added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4821): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4821): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
D/WifiService(  885): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4821): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): setDiscoveryMode: Discovery mode BLE is supported
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4821): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4821): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4821): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{e4fe656 u0 com.motorola.ccc.checkin/.CheckinService}
,I/chromium( 4821): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (40:291 vsyncs) (42:1054)
,I/CalendarProvider2( 4932): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4932): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=4971 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 4971): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 4874:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_4874/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{23fe054d u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 4821): Initializing JXcore engine
W/jxcore-log( 4821): JXcore engine is ready
,W/ProcessCpuTracker(  885): Skipping unknown process pid 4988
,W/ProcessCpuTracker(  885): Skipping unknown process pid 4991
,W/Thread-549( 4964): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10577 path="socket:[9821]" dev="sockfs" ino=9821 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-549( 4964): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10577 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-549( 4964): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10577 path="socket:[6608]" dev="sockfs" ino=6608 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-549( 4964): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10577 path="socket:[20237]" dev="sockfs" ino=20237 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,D/CAR.SERVICE( 4595): mConnectedToCar = false, abort
,W/jxcore-log( 4821): Starting JXcore engine
,E/ActivityThread( 4595): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@4443e9a that was originally bound here
E/ActivityThread( 4595): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@4443e9a that was originally bound here
E/ActivityThread( 4595): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 4595): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 4595): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 4595): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 4595): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4595): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4595): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4595): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 4595): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 4595): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 4595): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 4595): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 4595): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 4595): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 4595): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 4595): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 4595): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4595): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4595): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 4595): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4595): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4595): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 4595): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 4595): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@283089fd that was originally bound here
E/ActivityThread( 4595): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@283089fd that was originally bound here
E/ActivityThread( 4595): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 4595): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 4595): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 4595): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 4595): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4595): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 4595): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 4595): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 4595): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 4595): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 4595): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 4595): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 4595): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 4595): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 4595): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 4595): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4595): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4595): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 4595): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4595): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4595): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 4595): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  885): Unbind failed: could not find connection for android.os.BinderProxy@b47f0fe
,W/jxcore-log( 4821): Platform android
W/jxcore-log( 4821): 
,W/jxcore-log( 4821): Process ARCH arm
W/jxcore-log( 4821): 
,I/jxcore-log( 4821): JXcore Cordova bridge is ready!
I/jxcore-log( 4821): 
,W/jxcore-log( 4821): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4821): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 4821): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4821): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4821): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/PluginManager( 4821): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2538): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2538): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2538): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2538): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2538): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2538): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2538): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1413): onFinishInput()
,W/IInputConnectionWrapper( 4821): showStatusIcon on inactive InputConnection
,I/SFPerfTracer(  281):      triggers: (rate: 15:511) (compose: 0:1) (post: 0:1) (render: 0:2) (14:1007 frames) (15:1093)
D/SFPerfTracer(  281):        layers: (4:12) (FocusedStackFrame (0xb8dd1270): 0:17)* (DimLayer (0xb8dc8738): 0:8) (StatusBar (0xb8d42c40): 15:182) (NavigationBar (0xb8db0af8): 12:47) (com.android.systemui.ImageWallpaper (0xb8db6dc8): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8de1158): 0:55)- (Starting com.test.thalitest (0xb8dbd038): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8d3eb98): 15:71) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8dbd038): 0:4)* 
,I/SFPerfTracer(  281):      triggers: (rate: 15:511) (compose: 0:1) (post: 0:1) (render: 0:3) (17:1031 frames) (18:1119)
D/SFPerfTracer(  281):        layers: (4:10) (FocusedStackFrame (0xb8dd1270): 0:17)* (DimLayer (0xb8dc8738): 0:8) (StatusBar (0xb8d42c40): 0:186) (NavigationBar (0xb8db0af8): 0:47) (com.android.systemui.ImageWallpaper (0xb8db6dc8): 0:6)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8d3eb98): 2:81)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8dbd038): 18:27) 
,I/ActivityManager(  885): Killing 4595:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_4595/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 4163:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_4163/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {38cd71f1, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,V/AlarmManager(  885): done {38cd71f1, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [14ms]
,E/SQLiteLog( 4932): (284) automatic index on view_events(_id)
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,V/AlarmManager(  885): send {332ccc57, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {332ccc57, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  885): send {129fb344, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  885): done {129fb344, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/ActivityManager(  885): Killing 4061:com.google.process.gapps/u0a16 (adj 15): empty #7
,I/ActivityManager(  885): Killing 4418:com.android.vending/u0a32 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_4061/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_4418/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5040 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  885): send {1363c2d, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  885): done {1363c2d, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [44ms]
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 36.983ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 34.682ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 26.564ms
,I/ActivityManager(  885): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5070 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 5070): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5070): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5070): GMS http client unavailable, use old client
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310123, SEQNUM=4346, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-223, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/Finsky  ( 5040): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5040): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5040): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5040): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5040): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5040): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5040): Skipping gmscore version check
,I/ActivityManager(  885): Killing 4674:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_4674/cgroup.procs: No such file or directory
,D/Finsky  ( 5040): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5040): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 5040): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5040): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  885): Killing 4971:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_4971/cgroup.procs: No such file or directory
,D/Finsky  ( 5040): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  885): send {2a5d5ff9, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  885): done {2a5d5ff9, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [12ms]
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5040): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5140 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/Finsky  ( 5040): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 5140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5140): VM with version 2.1.0 has multidex support
,I/MultiDex( 5140): install
I/MultiDex( 5140): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5140): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5140): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b9b4cb7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5140): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1708): callingUid 10016, callindPid: 1708
,E/MDM     ( 1708): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 5140): Reading stored module config
,D/LocationInitializer( 1945): Restart initialization of location
,D/AuthorizationBluetoothService( 1708): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5140): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1708): No location to return for getLastLocation()
W/FusedLocationProvider( 1708): location=null
,D/CAR.SERVICE( 5140): Connecting to CarCallService...
,I/art     ( 5140): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5140): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5140): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5140): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5140): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5140): Creating a new PhoneAdapter instance
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5140): setListener: com.google.android.gms.car.dn@1d6406f2
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5140): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5140): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5140): Package validated; name: com.android.vending
,V/Finsky  ( 5040): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5040): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5040): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  885): send {32cb3151, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5040): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,I/art     (  885): Explicit concurrent mark sweep GC freed 19464(1004KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 21MB/31MB, paused 1.485ms total 120.016ms
,V/AlarmManager(  885): done {32cb3151, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [150ms]
,D/DeviceConnectionService( 1708): client connected with version: 8296000
,D/Finsky  ( 5040): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5040): [580] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5040): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5040): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:35000 mC
,I/ActivityManager(  885): Killing 3035:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10049/pid_3035/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5140): mConnectedToCar = false, abort
,E/ActivityThread( 5140): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@4443e9a that was originally bound here
E/ActivityThread( 5140): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@4443e9a that was originally bound here
E/ActivityThread( 5140): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5140): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5140): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5140): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5140): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5140): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5140): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5140): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5140): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5140): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5140): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5140): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5140): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5140): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5140): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5140): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5140): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5140): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5140): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5140): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5140): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@283089fd that was originally bound here
E/ActivityThread( 5140): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@283089fd that was originally bound here
E/ActivityThread( 5140): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5140): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5140): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5140): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5140): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5140): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5140): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5140): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5140): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5140): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5140): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5140): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5140): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5140): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5140): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5140): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5140): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5140): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5140): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5140): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5140): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  885): Unbind failed: could not find connection for android.os.BinderProxy@376011e
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2538):  Nonce Reponse 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  885): send {1c93aad6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {1c93aad6, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  885): send {1363c2d, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  885): done {1363c2d, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [10ms]
,D/Finsky  ( 5040): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5040): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=310, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309830, SEQNUM=4359, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14723, POWER_SUPPLY_CHARGE_COUNTER=-285, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=302, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309424, SEQNUM=4361, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-412, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 20985(1169KB) AllocSpace objects, 17(473KB) LOS objects, 39% free, 7MB/12MB, paused 942us total 39.135ms
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2538):  Nonce Reponse 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1708): onCreate
,I/ConfigService( 1708): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  885): send {2a0f64b8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  885): send {129fb344, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  885): done {2a0f64b8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,V/AlarmManager(  885): done {129fb344, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [11ms]
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
D/        (  885): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 223
,D/        (  885): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  885): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  885): Display changed displayId=0
,D/SurfaceFlinger(  281): Set power mode=0, type=0 flinger=0xb8ca4550
,D/qdhwcomposer(  281): hwc_blank: Blanking display: 0
,I/rmt_storage(  291): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8687820
I/rmt_storage(  291): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  291): wakelock acquired: 1, error no: 42
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1201113800)
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  291): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1201113800) wakelock released: 1, error no: 22
I/rmt_storage(  291): 
,I/rmt_storage(  291): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8687820
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  281): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  281): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  885): Excessive delay in setPowerMode(): 325ms
,I/PowerManagerService(  885): Sleeping (uid 1000)...
,I/WindowManager(  885): AOD feature not enabled!
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
E/msm8974_platform(  296): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  885): startHal
E/wifi    (  885): getStaticLongField sWifiHalHandle 0xa2df389c
D/wifi    (  885): halHandle = 0x0, mVM = 0xb7e3f310, mCls = 0x20190a
I/WifiNative-HAL(  885): Could not start hal
D/WifiStateMachine(  885): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  885): setSuspendOptimizations: 4 false
E/WifiStateMachine(  885): mSuspendOptNeedsDisabled 4
,I/WifiNative-HAL(  885): startHal
I/Keyboard.Facilitator( 1413): onFinishInput()
E/wifi    (  885): getStaticLongField sWifiHalHandle 0xa2df389c
D/wifi    (  885): halHandle = 0x0, mVM = 0xb7e3f310, mCls = 0x2018c6
I/WifiNative-HAL(  885): Could not start hal
,D/WifiStateMachine(  885): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: false
,D/        (  885): activate, handle: 1598182229, enabled: 0, index 0
E/        (  885): <BST> disable accel, orig state: 1
I/        (  885): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
E/WifiStateMachine(  885): setSuspendOptimizations: 4 true
E/WifiStateMachine(  885): mSuspendOptNeedsDisabled 0
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  885): send {10ba0293, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  885): done {10ba0293, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [9ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310139, SEQNUM=4377, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15825, POWER_SUPPLY_CHARGE_COUNTER=-637, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  885): send {1c93aad6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {1cae12d0, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {1cae12d0, *walarm*:com.google.android.intent.action.SEND_IDLE} [9ms]
,V/AlarmManager(  885): done {1c93aad6, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,E/global frequency( 2538): no tags to log
,D/Checkin ( 2538): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2538): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1545): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2538): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2538): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 2538): Explicit concurrent mark sweep GC freed 23414(1376KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 955us total 68.850ms
,D/BSUtils ( 2538): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1545): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 37344(2006KB) AllocSpace objects, 16(569KB) LOS objects, 40% free, 7MB/12MB, paused 509us total 34.441ms
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  885): Explicit concurrent mark sweep GC freed 15843(889KB) AllocSpace objects, 3(286KB) LOS objects, 33% free, 21MB/31MB, paused 1.452ms total 116.209ms
,D/BSUtils ( 2538): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2538): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2538): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1545): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2538): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2538): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/BSUtils ( 2538): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/global frequency( 2538): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2538): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2538): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2538): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2538): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2538):  Nonce Reponse 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/global frequency( 2538): BcsDSCheckin.events found events 2000
,D/Checkin ( 2538): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2538): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ClearcutLoggerApiImpl( 1708): disconnect managed GoogleApiClient
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 3486(137KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 715us total 26.560ms
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2538): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2538): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2538): unknown error code mapping for: 0
,I/global frequency( 2538): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2538): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2538): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2538): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  885): send {2a0f64b8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): send {2a298bfc, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  885): send {129fb344, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  885): done {2a0f64b8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,V/AlarmManager(  885): done {2a298bfc, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [11ms]
V/AlarmManager(  885): done {129fb344, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [12ms]
,I/VacuumService( 1708): Vacuum at: now=1457690864708 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1708): onCreate
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1708): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310330, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13020, POWER_SUPPLY_CHARGE_COUNTER=-888, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309945, SEQNUM=4385, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1268, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  885): send {1c93aad6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {1c93aad6, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2538):  Nonce Reponse 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  885): Explicit concurrent mark sweep GC freed 10465(506KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.447ms total 125.313ms
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1708): disconnect managed GoogleApiClient
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2538):  Nonce Reponse 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2538): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2538): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2538): Explicit concurrent mark sweep GC freed 39422(3MB) AllocSpace objects, 6(148KB) LOS objects, 39% free, 11MB/18MB, paused 1.120ms total 61.138ms
,D/MMApiWebService( 2538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2538): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2538): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2538): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {1c93aad6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {332ccc57, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  885): send {21cd0c7, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  885): done {332ccc57, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [23ms]
,V/AlarmManager(  885): done {21cd0c7, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [38ms]
,V/AlarmManager(  885): done {1c93aad6, *alarm*:android.intent.action.TIME_TICK} [50ms]
,I/EventLogService( 1945): Aggregate from 1457690022452 (log), 1457690022452 (data)
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5343): 
D/AndroidRuntime( 5343): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5343): CheckJNI is OFF
D/AndroidRuntime( 5343): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10577 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 4821:com.test.thalitest/u0a577 (adj 13): stop com.test.thalitest
D/WifiService(  885): Client connection lost with reason: 4
W/PackageSettings(  885): Skipping PackageSetting{abe2d9b com.example.hello/10568} due to missing metadata
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10577 user=0: pkg removed
I/art     ( 2968): Explicit concurrent mark sweep GC freed 3909(874KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 7MB/12MB, paused 517us total 34.436ms
W/ActivityManager(  885): Spurious death for ProcessRecord{346aa8b6 4821:com.test.thalitest/u0a577}, curProc for 4821: null
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1708): Ignoring removeGeofence because network location is disabled.
I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
I/Decoder ( 1413): createOrResetDecoder
I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5372 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1564): Explicit concurrent mark sweep GC freed 7548(545KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 505us total 142.478ms
I/art     (  885): Explicit concurrent mark sweep GC freed 9513(755KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/31MB, paused 1.575ms total 133.106ms
I/art     (  885): WaitForGcToComplete blocked for 26.732ms for cause Explicit
I/art     ( 1945): Explicit concurrent mark sweep GC freed 2305(163KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 998us total 156.424ms
I/ConfigService( 1708): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/VoicemailCleanupService( 5372): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5397 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (3:372 vsyncs) (5:1159)
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/ContactLocale( 5372): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  885): Explicit concurrent mark sweep GC freed 5244(270KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 4.215ms total 225.014ms
W/asset   ( 5397): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5397): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5418 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4932:com.android.providers.calendar/u0a5 (adj 15): empty #7
I/Launcher( 1564): Deferring update until onResume
D/AndroidRuntime( 5343): Shutting down VM
W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_4932/cgroup.procs: No such file or directory
W/ContextImpl( 5418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1945): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1945): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1708): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1708): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1945): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5443 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1945): doRemovePackageData com.test.thalitest
W/Launcher( 1564): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@27db632c new=com.google.android.velvet.VelvetApplication@27db632c
I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5467 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
