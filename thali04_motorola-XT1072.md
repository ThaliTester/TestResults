#### Test 6275440319c4f54_thali04_motorola-XT1072 Logs


```
--------- beginning of main
W/art     ( 4707): Suspending all threads took: 20.156ms
--------- beginning of system
I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4742 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 4707): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4707): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 4707): Unsupported mime video/mpeg2
I/VideoCapabilities( 4707): Unsupported profile 4 for video/mp4v-es
D/MMApiWSBase( 2512): doRequest(): v1/cs/checkin resp length: 4
D/CCE     ( 2512): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2512): AppWSProxy - sendAIDLWSResponse() sending reponse
W/VideoCapabilities( 4707): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4707): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4707): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4707): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  879): Killing 4526:com.google.android.music:main/u0a80 (adj 15): empty #7
I/global frequency( 2512): BcsCore.status() called with error code=ERROR_OK
D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_4526/cgroup.procs: No such file or directory
I/vclib   ( 4707): onServiceConnected
W/Babel   ( 4707): Attempted to change video mute state without an active call.
I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4769 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
D/CheckinProvider(  879): 105 events delete 0 left
I/ActivityManager(  879): Killing 4138:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
I/CalendarProvider2( 4678): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/PhoneMonitor( 4769): Register our PhoneStateListener
W/ContentResolver( 4678): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/global frequency( 2512): BcsDSCheckin.events found events 0
D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 2512): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2512): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/AndroidRuntime( 4759): 
D/AndroidRuntime( 4759): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4759): CheckJNI is OFF
W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_4138/cgroup.procs: No such file or directory
I/global frequency( 2512): BcsTimer.onReceive checkin completed (-1152565159:ERROR_OK)
I/ActivityManager(  879): Killing 4613:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_4613/cgroup.procs: No such file or directory
V/SetupWizard( 4769): Connected to Gservices successfully
I/ActivityManager(  879): Killing 4583:com.google.android.gm/u0a63 (adj 15): empty #7
W/DataUsage( 2512): invalid counter update blocked: 'err' by 0
D/Checkin ( 2512): publish the event [tag = MOT_CCE event name = LOG]
W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_4583/cgroup.procs: No such file or directory
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4804 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/AndroidRuntime( 4759): Calling main entry com.android.commands.am.Am
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (173 us)
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4759): Shutting down VM
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4823 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 2512): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2512): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2512): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2512): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2512): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2512): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2512): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2512): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2512): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2512): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2512): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2512): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2512): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  879): Activity reported stop, but no longer stopping: ActivityRecord{273a6a4a u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,W/ProcessCpuTracker(  879): Skipping unknown process pid 4759
,I/WebViewFactory( 4823): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4823): Time to load native libraries: 3 ms (timestamps 8393-8396)
I/LibraryLoader( 4823): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4823): Binding Chromium to main looper Looper (main, tid 1) {3bfccd4d}
I/LibraryLoader( 4823): Expected native library version number "",actual native library version number ""
I/chromium( 4823): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4823): Initializing chromium process, singleProcess=true
W/art     ( 4823): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4823): ApplicationContext is null in ApplicationStatus
,W/chromium( 4823): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4823): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4823): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4823): Local Branch: 
I/Adreno-EGL( 4823): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4823): Local Patches: NONE
I/Adreno-EGL( 4823): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4861 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SFPerfTracer(  279):      triggers: (rate: 15:475) (compose: 0:1) (post: 0:1) (render: 0:2) (7:920 frames) (8:993)
D/SFPerfTracer(  279):        layers: (5:12) (FocusedStackFrame (0xb8b0aa80): 0:11)* (DimLayer (0xb8b10038): 0:5) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8aae350): 0:23)- (StatusBar (0xb8ab16b0): 1:123) (NavigationBar (0xb8a68ad0): 0:34) (com.android.systemui.ImageWallpaper (0xb8a6a7e8): 0:34)* (Starting com.motorola.ccc.ota (0xb8a6df98): 0:37)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b010f8): 8:45) (Starting com.test.thalitest (0xb8aae350): 8:11) 
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@331b8797:true
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4883 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 4707): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4707): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4707): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 4823): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4823): onDetachedFromWindow called when already detached. Ignoring
,W/System  ( 4707): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4707): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4913 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 4657:com.motorola.context/u0a8 (adj 15): empty #7
,D/SystemWebViewEngine( 4823): CordovaWebView is running on device made by: motorola
,I/ContactLocale( 4883): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/art     ( 4823): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4823): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_4657/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 4678:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/asset   ( 4913): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 4913): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4913): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4913): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_4678/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 4823): Render dirty regions requested: true
,D/Atlas   ( 4823): Validating map...
,W/chromium( 4823): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  879): Killing 4742:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_4742/cgroup.procs: No such file or directory
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f122a4e new=com.google.android.velvet.VelvetApplication@3f122a4e
,I/UpdateIcingCorporaServi( 4804): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1953): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 1953): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4947 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  879): Explicit concurrent mark sweep GC freed 17438(866KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.048ms total 131.112ms
,D/WearableController( 1953): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/OpenGLRenderer( 4823): Initialized EGL, version 1.4
I/Icing   ( 1953): updateResources: need to parse f{com.google.android.gms}
,D/OpenGLRenderer( 4823): Enabling debug mode 0
,W/ResourcesManager( 4947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1347
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s348ms
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 52250(3MB) AllocSpace objects, 34(544KB) LOS objects, 39% free, 13MB/22MB, paused 7.962ms total 165.390ms
,E/Adreno-ES20( 4823): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4823): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/UpdateIcingCorporaServi( 4804): UpdateCorporaTask done [took 319 ms] updated apps [took 319 ms] 
I/ActivityManager(  879): Killing 4769:com.google.android.setupwizard/u0a35 (adj 15): empty #7
W/BindingManager( 4823): Cannot call determinedVisibility() - never saw a connection for the pid: 4823
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_4769/cgroup.procs: No such file or directory
,D/JsMessageQueue( 4823): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4989 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.332ms
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 23.270ms
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (21:236 vsyncs) (23:1037)
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.697ms
,I/ActivityManager(  879): Killing 3033:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10049/pid_3033/cgroup.procs: No such file or directory
,E/Adreno-ES20( 4823): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4823): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/Finsky  ( 4989): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/jxcore_app_log( 4823): JniHelper::setJavaVM(0xb8986310), pthread_self() = -1194212264
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f1c829 added. We now have 1 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4823): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4823): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4823): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f9c8dc added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4823): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  879): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4823): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 4823): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4823): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4823): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4823): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4823): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4823): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4823): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
,W/System.err( 4823): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4823): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4823): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4823): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4823): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4823): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 4823): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cb5bde5 added. We now have 2 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4823): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4823): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5bd0ba added. We now have 2 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4823): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 4823): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4823): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
,W/System.err( 4823): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4823): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4823): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4823): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4823): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4823): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4823): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4823): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4823): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4823): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4823): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Finsky  ( 4989): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4989): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4989): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 4989): Skipping gmscore version check
,D/Finsky  ( 4989): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4989): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  879): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5034 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 4861:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_4861/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Finsky  ( 4989): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4989): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1953): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Gmail   ( 5034): getAccountsCursor
,D/ActivityThread( 5034): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Icing   ( 1953): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  879): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5060 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1953): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5060): EasService.onCreate
,I/Exchange( 5060): RestartPingTask
,I/Exchange( 5060): RestartPingsTask did not start any pings.
I/Exchange( 5060): PSS stopIfIdle
I/Exchange( 5060): PSS has no active accounts; stopping service.
,W/GAV2    ( 5034): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 5034): Observing account changes for notifications
,I/Gmail   ( 5034): getAccountsCursor
,I/Exchange( 5060): onDestroy
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Killing 4913:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_4913/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5099 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Killing 4804:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_4804/cgroup.procs: No such file or directory
,W/ResourcesManager( 5099): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/SQLiteLog( 5034): (283) recovered 26 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5034): notifyAccountChanged
,I/Gmail   ( 5034): getAccountsCursor
,I/Gmail   ( 5034): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  879): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5121 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5034): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Killing 4883:android.process.acore/u0a7 (adj 13): empty #7
,I/Gmail   ( 5034): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5034): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_4883/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5034): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5121): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  879): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5144 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5144): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5121): PlayLogger.onLoggerConnected
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5165 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CalendarProvider2( 5144): Created com.android.providers.calendar.CalendarAlarmManager@16094276(com.android.providers.calendar.CalendarProvider2@11757077)
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Killing 4947:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_4947/cgroup.procs: No such file or directory
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ContactLocale( 5165): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  879): Explicit concurrent mark sweep GC freed 11256(552KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.822ms total 117.281ms
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5185 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5205 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 4989:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_4989/cgroup.procs: No such file or directory
,W/asset   ( 5205): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5205): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5205): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5205): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5226 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 3118:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_3118/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5247 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 5247): Gservices pushing to system: true; secure/global: true
,I/art     ( 1953): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,I/GoogleHttpClient( 5247): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5247): GMS http client unavailable, use old client
,D/PkgBroadcastIntentOp( 1953): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1953): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/UpdateIcingCorporaServi( 5226): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  879): Killing 5060:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,I/CalendarProvider2( 5144): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5144): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_5060/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Killing 5034:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_5034/cgroup.procs: No such file or directory
,D/AsyncTaskServiceImpl( 1953): Submit a task: k
,D/k       ( 1953): Processing package: com.test.thalitest
,D/GassUtils( 1953): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1953): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1953): Using Auth Proxy for data requests.
W/BaseAppContext( 1953): Using Auth Proxy for data requests.
,W/BaseAppContext( 1953): Using Auth Proxy for data requests.
,I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5291 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 583us total 22.950ms
,W/BaseAppContext( 1953): Using Auth Proxy for data requests.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.204ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.513ms
,W/BaseAppContext( 1953): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi( 5226): UpdateCorporaTask done [took 412 ms] updated apps [took 412 ms] 
,I/ActivityManager(  879): Killing 5099:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_5099/cgroup.procs: No such file or directory
,I/PeopleDatabaseHelper( 1953): cleanUpNonGplusAccounts done.
,I/GAv4    ( 5291): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5291):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5291):   adb logcat -s GAv4
,W/GAv4    ( 5291): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5291): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5291): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5291): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5291): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5329 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5144:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/ResourcesManager( 5291): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5291): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_5144/cgroup.procs: No such file or directory
,V/AlarmManager(  879): send {14bc6246, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/ActivityManager(  879): Killing 4707:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 5329): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 1953): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,V/JNIHelp ( 5291): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 1953): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/Icing   ( 1953): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,W/System  ( 5291): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5291): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_4707/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1953): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5366 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5185:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_5185/cgroup.procs: No such file or directory
,D/Finsky  ( 5366): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5366): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5366): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5366): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5366): Skipping gmscore version check
,I/ActivityManager(  879): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5409 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 5366): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5366): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5366): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5366): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5366): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Killing 5205:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Gmail   ( 5409): getAccountsCursor
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_5205/cgroup.procs: No such file or directory
,D/ActivityThread( 5409): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5433 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/chromium( 4823): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 4823): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,W/GAV2    ( 5409): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5409): Observing account changes for notifications
,D/3CDM.DeviceAdminSetupReceiver( 2512): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2512): time to show notification
,I/Gmail   ( 5409): getAccountsCursor
,W/ResourcesManager( 1288): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5467 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  879): Explicit concurrent mark sweep GC freed 13764(698KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 4.319ms total 140.136ms
,I/Exchange( 5433): EasService.onCreate
,I/ActivityManager(  879): Killing 5226:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Exchange( 5433): RestartPingTask
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_5226/cgroup.procs: No such file or directory
,E/ActivatableNotificationView( 1288):  oops Width=0 ActualHeight=128
,I/Exchange( 5433): RestartPingsTask did not start any pings.
I/Exchange( 5433): PSS stopIfIdle
,I/Exchange( 5433): PSS has no active accounts; stopping service.
,I/Exchange( 5433): onDestroy
W/ResourcesManager( 5467): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
I/ActivityManager(  879): Killing 5291:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,E/SQLiteLog( 5409): (283) recovered 27 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5409): notifyAccountChanged
,I/Gmail   ( 5409): getAccountsCursor
,I/Gmail   ( 5409): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5409): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  879): failed to open /acct/uid_10057/pid_5291/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5409): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5409): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  879): Killing 5165:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_5165/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5409): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5499 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5499): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5499): Created com.android.providers.calendar.CalendarAlarmManager@16094276(com.android.providers.calendar.CalendarProvider2@11757077)
,V/AlarmManager(  879): done {14bc6246, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [1621ms]
,E/SQLiteLog( 5499): (284) automatic index on view_events(_id)
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 5121): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5121): Thread[GAThread,5,main]: No campaign data found.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:38000 mC
,I/CalendarProvider2( 5499): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5499): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  879): Killing 5329:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_5329/cgroup.procs: No such file or directory
,D/Finsky  ( 5366): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  879): send {38fa9d42, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  879): send {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {38fa9d42, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [9ms]
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.39 rxSuccessRate=3.85 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=26339 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  879): done {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [15ms]
,E/WifiStateMachine(  879): [1,457,968,377,401 ms] noteScanstart no scan source
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  879): [1,457,968,377,468 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3448a2b1 sup_state=COMPLETED debouncing=false
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qtaguid ( 5366): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5366): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5366): untagSocket(37) failed with errno -22
,D/Finsky  ( 5366): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  879): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5555 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5555): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5555): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SFPerfTracer(  279):      triggers: (rate: 15:475) (compose: 0:1) (post: 0:1) (render: 0:2) (38:1029 frames) (39:1118)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb8b0aa80): 0:14)* (DimLayer (0xb8b10038): 0:7)* (StatusBar (0xb8ab16b0): 39:162) (NavigationBar (0xb8a68ad0): 0:34) (com.android.systemui.ImageWallpaper (0xb8a6a7e8): 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8b010f8): 0:47)- (Starting com.test.thalitest (0xb8aae350): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a6ea20): 0:57) 
,I/MultiDex( 5555): VM with version 2.1.0 has multidex support
I/MultiDex( 5555): install
,I/MultiDex( 5555): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5555): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5555): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5555): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1095361: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5555): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 5555): Reading stored module config
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,E/MDM     ( 1736): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1953): Restart initialization of location
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,V/AlarmManager(  879): send {12f765fa, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  879): done {12f765fa, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [37ms]
,D/NativeLibraryUtils( 5555): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5555): Connecting to CarCallService...
,I/art     ( 5555): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5555): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/qtaguid ( 5366): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5366): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5366): untagSocket(37) failed with errno -22
,D/CAR.SERVICE( 5555): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5555): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5555): Creating a new PhoneAdapter instance
,W/ActivityManager(  879): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5555): setListener: com.google.android.gms.car.dn@3670f0d
W/ActivityManager(  879): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5555): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5555): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5555): Package validated; name: com.android.vending
,V/Finsky  ( 5366): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5366): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5366): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5366): untagSocket(37) failed with errno -22
,V/AlarmManager(  879): send {75da7ea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {75da7ea, *alarm*:android.intent.action.TIME_TICK} [34ms]
,W/ActivityManager(  879): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5366): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5366): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5366): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5366): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  879): send {1a3dce76, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  879): done {1a3dce76, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [16ms]
,D/DeviceConnectionService( 1736): client connected with version: 8296000
,D/Finsky  ( 5366): [644] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5366): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5366): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 5409): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  879): Killing 5433:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_5433/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {1a5dd505, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {1a5dd505, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,D/CAR.SERVICE( 5555): mConnectedToCar = false, abort
,E/ActivityThread( 5555): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@6aea55 that was originally bound here
E/ActivityThread( 5555): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@6aea55 that was originally bound here
E/ActivityThread( 5555): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5555): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5555): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5555): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5555): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5555): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5555): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5555): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5555): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5555): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5555): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5555): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5555): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5555): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5555): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5555): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5555): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5555): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5555): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5555): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5555): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5555): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5555): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5555): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@255685a4 that was originally bound here
E/ActivityThread( 5555): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@255685a4 that was originally bound here
E/ActivityThread( 5555): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5555): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5555): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5555): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5555): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5555): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5555): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5555): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5555): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5555): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5555): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5555): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5555): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5555): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5555): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5555): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5555): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5555): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5555): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5555): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5555): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5555): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  879): Unbind failed: could not find connection for android.os.BinderProxy@17b9695a
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Waited long enough for: ServiceRecord{10455fc2 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:36000 mC
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Killing 5467:com.motorola.context/u0a8 (adj 15): empty #7
,I/ActivityManager(  879): Killing 5409:com.google.android.gm/u0a63 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_5467/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_5409/cgroup.procs: No such file or directory
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  879): send {373c7068, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {373c7068, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [21ms]
,V/AlarmManager(  879): done {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [24ms]
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.13 rxSuccessRate=2.54 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=43401 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN try full band scan age=43401 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN bump interval =45000
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  879): [1,457,968,394,462 ms] noteScanstart no scan source
,D/Finsky  ( 5366): [635] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5366): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  879): [1,457,968,394,966 ms] noteScanEnd no scan source
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3448a2b1 sup_state=COMPLETED debouncing=false
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:35000 mC
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/art     (  879): Explicit concurrent mark sweep GC freed 28492(1331KB) AllocSpace objects, 3(140KB) LOS objects, 33% free, 20MB/31MB, paused 1.735ms total 147.966ms
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311325, SEQNUM=4358, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-110, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {1a5dd505, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {1a5dd505, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,E/ActivityThread( 1953): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  879): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 196685, reason: UserStart
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {177bc9b2, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  879): send {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {177bc9b2, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [11ms]
V/AlarmManager(  879): done {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [12ms]
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.02 rxSuccessRate=0.08 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=21472 interval=45000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  879): [1,457,968,415,935 ms] noteScanstart no scan source
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  879): [1,457,968,416,003 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3448a2b1 sup_state=COMPLETED debouncing=false
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1736): Vacuum at: now=1457968416111 tag=VacuumService
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=305, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310884, SEQNUM=4364, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-143, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/BackupManagerService(  879): Timeout restoring application @pm@
,W/BackupManagerService(  879): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1736): Restore processing aborted, no more packages
,E/BackupManagerService(  879): Failure getting next package name
E/BackupManagerService(  879): Duplicate finish
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {ecaedd4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [4ms]
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.01 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=35380 interval=45000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  879): [1,457,968,429,844 ms] noteScanstart no scan source
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  879): [1,457,968,429,906 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3448a2b1 sup_state=COMPLETED debouncing=false
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1736): onCreate
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1736): onDestroy
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {75da7ea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {75da7ea, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,V/AlarmManager(  879): send {1a5dd505, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {1a5dd505, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/PowerManagerService(  879): Nap time (uid 1000)...
,I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  879): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  879): Build Date: 10/28/14 Tue
I/Adreno-EGL(  879): Local Branch: 
I/Adreno-EGL(  879): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  879): Local Patches: NONE
I/Adreno-EGL(  879): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (9:318 vsyncs) (11:1141)
,D/        (  879): activate, handle: 1598182242, enabled: 0, index 2
D/        (  879): BstSensorExt: id=1598182242, en=0
D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 224
,D/        (  879): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  879): Display changed displayId=0
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb89e0550
,D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb745a820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1220172488)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1220172488) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb745a820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  879): Excessive delay in setPowerMode(): 340ms
,I/WindowManager(  879): AOD feature not enabled!
,I/PowerManagerService(  879): Sleeping (uid 1000)...
,I/SFPerfTracer(  279):       trigger: frame rate (-27.669%)	(43.398 fps)	(23.042 ms) 	(3 drops)	(16 frames)
I/SFPerfTracer(  279):      triggers: (rate: 16:479) (compose: 0:1) (post: 0:1) (render: 0:2) (16:1047 frames) (17:1148)
D/SFPerfTracer(  279):        layers: (4:10) (FocusedStackFrame (0xb8b0aa80): 0:14)* (DimLayer (0xb8b10038): 0:7)* (StatusBar (0xb8ab16b0): 0:167) (NavigationBar (0xb8a68ad0): 0:34) (com.android.systemui.ImageWallpaper (0xb8a6a7e8): 0:34)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a6ea20): 0:57) (ColorFade (0xb8a6d5b8): 17:19) 
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/LaunchCheckinHandler(  879): cleanup(): cleared. Last call was 67175 ms ago
,D/JX-Cordova( 4823): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4823): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@238cbb6b added. We now have 3 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4823): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4823): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): load: Already loaded
,D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23c896c8 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4823): addListener: New listener added - the number of listeners is now 1
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4823): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,W/System.err( 4823): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4823): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4823): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4823): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4823): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4823): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
,W/System.err( 4823): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4823): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4823): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4823): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4823): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4823): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4823): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  879): do suspend false
,I/Keyboard.Facilitator( 1413): onFinishInput()
,D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  879): <BST> disable accel, orig state: 1
E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
,I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  879): do suspend true
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  879): send {31706db0, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {31706db0, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [9ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311885, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10717, POWER_SUPPLY_CHARGE_COUNTER=-294, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  879): send {146a8429, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {146a8429, *walarm*:com.google.android.intent.action.SEND_IDLE} [6ms]
,I/PhenotypeConfigurator( 1736): Scheduling Phenotype for one-off execution 14183 seconds from now (1457968476119)
,I/PhenotypeFlagCommitter( 1736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1736): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1736): Background sticky concurrent mark sweep GC freed 109166(5MB) AllocSpace objects, 12(192KB) LOS objects, 26% free, 16MB/22MB, paused 7.088ms total 97.900ms
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c31e46f)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11b2457c)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13fb8e05)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@43f2e5a)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a2588b)
,E/global frequency( 2512): no tags to log
,D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2512): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2512): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2512): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2512): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 56559(3MB) AllocSpace objects, 35(1243KB) LOS objects, 39% free, 7MB/12MB, paused 763us total 44.882ms
,I/art     ( 2512): Explicit concurrent mark sweep GC freed 23811(1530KB) AllocSpace objects, 4(87KB) LOS objects, 40% free, 11MB/19MB, paused 1.061ms total 64.457ms
,D/BSUtils ( 2512): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2512): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2512): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  879): Explicit concurrent mark sweep GC freed 42169(2013KB) AllocSpace objects, 2(218KB) LOS objects, 33% free, 20MB/31MB, paused 2.044ms total 144.285ms
,D/BSUtils ( 2512): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2512): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2512): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2512): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2512): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2512): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2512): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2512): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2512): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 1736): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  879): send {34ca6655, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  879): done {34ca6655, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [10ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  879): send {75da7ea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {2019a86a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  879): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5754 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  879): done {75da7ea, *alarm*:android.intent.action.TIME_TICK} [108ms]
,I/GAv4    ( 5754): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5754):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5754):   adb logcat -s GAv4
,W/GAv4    ( 5754): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5754): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5754): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AlarmManager(  879): done {2019a86a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [303ms]
I/ActivityManager(  879): Killing 5499:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_5499/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1736): onCreate
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1736): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311773, SEQNUM=4390, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9615, POWER_SUPPLY_CHARGE_COUNTER=-504, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311678, SEQNUM=4392, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-807, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {75da7ea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {75da7ea, *alarm*:android.intent.action.TIME_TICK} [34ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {75da7ea, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {12f765fa, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): send {3121e136, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  879): done {12f765fa, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [24ms]
,V/AlarmManager(  879): done {75da7ea, *alarm*:android.intent.action.TIME_TICK} [52ms]
,V/AlarmManager(  879): done {3121e136, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [58ms]
,I/EventLogService( 1953): Aggregate from 1457968352264 (log), 1457967546258 (data)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {75da7ea, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  879): send {3f0a70d3, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  879): done {3f0a70d3, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [19ms]
,V/AlarmManager(  879): done {75da7ea, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311545, SEQNUM=4396, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-55, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2407): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5799): 
D/AndroidRuntime( 5799): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5799): CheckJNI is OFF
D/AndroidRuntime( 5799): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 4823:com.test.thalitest/u0a109 (adj 0): stop com.test.thalitest
I/WindowState(  879): WIN DEATH: Window{251df595 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
W/PackageSettings(  879): Skipping PackageSetting{3a91b19c com.example.hello/10568} due to missing metadata
I/ActivityManager(  879):   Force finishing activity ActivityRecord{13832242 u0 com.test.thalitest/.MainActivity t9}
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  879): Spurious death for ProcessRecord{1c048410 4823:com.test.thalitest/u0a109}, curProc for 4823: null
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
I/ActivityManager(  879):   Force finishing activity ActivityRecord{13832242 u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  879): Duplicate finish request for ActivityRecord{13832242 u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 2966): Explicit concurrent mark sweep GC freed 9976(2MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 7MB/12MB, paused 850us total 32.219ms
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5823 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
W/SQLiteConnectionPool( 1953): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/art     ( 1953): Explicit concurrent mark sweep GC freed 3799(243KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 898us total 137.872ms
I/art     ( 1567): Explicit concurrent mark sweep GC freed 2224(119KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 463us total 123.205ms
I/Decoder ( 1413): createOrResetDecoder
D/OtaApp  ( 2512): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2512): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2512): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2512): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2512): publish the event [tag = MOT_OTA event name = LOG]
I/ConfigService( 1736): onCreate
D/OtaApp  ( 2512): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2512): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2512): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  879): Explicit concurrent mark sweep GC freed 21145(1637KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 20MB/31MB, paused 3.469ms total 190.696ms
I/art     (  879): WaitForGcToComplete blocked for 107.377ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
D/VoicemailCleanupService( 5823): Cleaning up data for package: com.test.thalitest
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
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5855 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5823): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task.xml
I/ActivityManager(  879): Killing 5121:com.google.android.calendar/u0a49 (adj 15): empty #7
W/InputMethodManagerService(  879): Got RemoteException sending setActive(false) notification to pid 4823 uid 10109
I/Keyboard.Facilitator( 1413): onFinishInput()
I/art     (  879): Explicit concurrent mark sweep GC freed 4913(280KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 3.068ms total 240.780ms
W/libprocessgroup(  879): failed to open /acct/uid_10049/pid_5121/cgroup.procs: No such file or directory
W/asset   ( 5855): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5855): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5855): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5855): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Launcher( 1567): Deferring update until onResume
D/AndroidRuntime( 5799): Shutting down VM
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5877 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.508ms
I/ActivityManager(  879): Killing 5555:com.google.android.gms:car/u0a16 (adj 15): empty #7
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 21.562ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.986ms
W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_5555/cgroup.procs: No such file or directory
W/ContextImpl( 5877): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  879): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5896 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5914 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5366:com.android.vending/u0a32 (adj 15): empty #7
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
