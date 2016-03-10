#### Test 613623667b1a8f4_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/UpdateIcingCorporaServi( 4830): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/GAv4    ( 4849): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4849):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4849):   adb logcat -s GAv4
W/GAv4    ( 4849): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4849): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4849): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4849): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
I/UpdateIcingCorporaServi( 4830): UpdateCorporaTask done [took 231 ms] updated apps [took 231 ms] 
--------- beginning of system
I/ActivityManager(  883): Killing 4537:com.android.providers.calendar/u0a5 (adj 15): empty #7
W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_4537/cgroup.procs: No such file or directory
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4849): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 4849): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4849): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4909 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 3498:com.android.defcontainer/u0a10 (adj 15): empty #7
W/libprocessgroup(  883): failed to open /acct/uid_10010/pid_3498/cgroup.procs: No such file or directory
D/AndroidRuntime( 4895): 
D/AndroidRuntime( 4895): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4895): CheckJNI is OFF
W/ResourcesManager( 4909): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Icing   ( 1904): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
W/art     ( 4849): Suspending all threads took: 9.144ms
V/JNIHelp ( 4849): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Icing   ( 1904): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
W/System  ( 4849): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4849): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 4895): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (170 us)
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4895): Shutting down VM
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4951 uid=10573 gids={50573, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4970 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 3042:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_3042/cgroup.procs: No such file or directory
,I/WebViewFactory( 4951): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  883): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=4988 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.043ms
,I/LibraryLoader( 4951): Time to load native libraries: 6 ms (timestamps 1559-1565)
I/LibraryLoader( 4951): Expected native library version number "",actual native library version number ""
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 19.839ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.687ms
,V/WebViewChromiumFactoryProvider( 4951): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 4951): Expected native library version number "",actual native library version number ""
,I/chromium( 4951): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SFPerfTracer(  280):      triggers: (rate: 15:523) (compose: 0:1) (post: 0:1) (render: 0:2) (15:912 frames) (16:980)
D/SFPerfTracer(  280):        layers: (4:12) (FocusedStackFrame (0xb72f8c68): 1:11)* (DimLayer (0xb7383e80): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb736d148): 0:43)- (StatusBar (0xb73a8e68): 14:154) (NavigationBar (0xb73aa0f8): 11:31) (com.android.systemui.ImageWallpaper (0xb73abfb0): 0:35)* (Starting com.motorola.ccc.ota (0xb73af5e8): 0:31)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb739f950): 15:42) (Starting com.test.thalitest (0xb73af5e8): 1:3)* 
,I/GservicesProvider( 4988): Gservices pushing to system: true; secure/global: true
I/Icing   ( 1904): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/BrowserStartupController( 4951): Initializing chromium process, singleProcess=true
,W/art     ( 4951): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4951): ApplicationContext is null in ApplicationStatus
,W/chromium( 4951): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4951): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4951): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4951): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4951): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4951): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4951): Local Branch: 
I/Adreno-EGL( 4951): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4951): Local Patches: NONE
I/Adreno-EGL( 4951): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/GoogleHttpClient( 4988): GMS http client unavailable, use old client
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c706040:true
,D/BluetoothAdapter( 4951): 343958975: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 1904): Explicit concurrent mark sweep GC freed 64163(3MB) AllocSpace objects, 19(304KB) LOS objects, 24% free, 14MB/19MB, paused 2.396ms total 120.909ms
,I/GoogleHttpClient( 4988): GMS http client unavailable, use old client
,I/Icing   ( 1904): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,D/Finsky  ( 4970): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/art     ( 4951): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4951): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4951): CordovaWebView is running on device made by: motorola
,W/art     ( 4951): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4951): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4951): Render dirty regions requested: true
,D/Atlas   ( 4951): Validating map...
,W/chromium( 4951): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4951): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4951): Enabling debug mode 0
,D/Finsky  ( 4970): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4970): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 4970): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1048
,I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s48ms
,I/Keyboard.Facilitator( 1404): onFinishInput()
,E/Adreno-ES20( 4951): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4951): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4951): Cannot call determinedVisibility() - never saw a connection for the pid: 4951
,I/art     (  883): Explicit concurrent mark sweep GC freed 13105(659KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.936ms total 152.072ms
,D/Finsky  ( 4970): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4970): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4970): Skipping gmscore version check
,I/ActivityManager(  883): Killing 4774:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_4774/cgroup.procs: No such file or directory
,D/Finsky  ( 4970): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4970): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 4970): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 4796:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_4796/cgroup.procs: No such file or directory
,E/Adreno-ES20( 4951): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4951): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  883): Killing 4160:com.google.android.talk/u0a70 (adj 15): empty #7
,D/JsMessageQueue( 4951): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_4160/cgroup.procs: No such file or directory
,D/jxcore_app_log( 4951): JniHelper::setJavaVM(0xb8711310), pthread_self() = -1196977560
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ae68ec added. We now have 1 listener(s)
,D/Finsky  ( 4970): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/AlarmManager(  883): send {1387ae6a, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  883): done {1387ae6a, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [8ms]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): setBluetoothMacAddress: 08:00:00:10:DD:3C
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4951): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4951): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4951): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4951): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9da6bb added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4951): addListener: New listener added - the number of listeners is now 1
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  883): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4951): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4951): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4951): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4951): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4951): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 4951): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Finsky  ( 4970): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5097 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/Finsky  ( 4970): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 5097): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5097): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5097): VM with version 2.1.0 has multidex support
I/MultiDex( 5097): install
I/MultiDex( 5097): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5097): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5097): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5097): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5097): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1704): callingUid 10016, callindPid: 1704
,D/ChimeraCfgMgr( 5097): Reading stored module config
,D/LocationInitializer( 1904): Restart initialization of location
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1704): [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/AlarmManager(  883): send {2a5abc18, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5097): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/ActivityManager(  883): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5129 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 5097): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1704): No location to return for getLastLocation()
,W/FusedLocationProvider( 1704): location=null
,W/ResourcesManager( 5129): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 5097): Connecting to CarCallService...
,I/CalendarProvider2( 5129): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,V/AlarmManager(  883): done {2a5abc18, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [225ms]
,I/art     ( 5097): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5097): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/SQLiteLog( 5129): (284) automatic index on view_events(_id)
,D/CAR.SERVICE( 5097): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5097): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5097): Creating a new PhoneAdapter instance
,W/ActivityManager(  883): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5097): setListener: com.google.android.gms.car.dn@2305b52
,W/ActivityManager(  883): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5097): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5097): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5097): Package validated; name: com.android.vending
,V/Finsky  ( 4970): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4970): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4970): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  883): send {3b420894, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 4970): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,V/AlarmManager(  883): done {3b420894, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [22ms]
,D/DeviceConnectionService( 1704): client connected with version: 8296000
,D/Finsky  ( 4970): [575] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4970): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4970): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4970): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  883): Killing 4830:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_4830/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 2951:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10049/pid_2951/cgroup.procs: No such file or directory
,D/TaskPersister(  883): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/CalendarProvider2( 5129): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5129): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5161 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 4849:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/jxcore-log( 4951): Initializing JXcore engine
W/jxcore-log( 4951): JXcore engine is ready
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_4849/cgroup.procs: No such file or directory
,W/ResourcesManager( 5161): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/Thread-565( 5090): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10573 path="socket:[5796]" dev="sockfs" ino=5796 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-565( 5090): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10573 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-565( 5090): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10573 path="socket:[7438]" dev="sockfs" ino=7438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-565( 5090): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10573 path="socket:[23694]" dev="sockfs" ino=23694 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4951): Starting JXcore engine
,I/ActivityManager(  883): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5184 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 4747:android.process.acore/u0a7 (adj 15): empty #7
,W/jxcore-log( 4951): Platform android
W/jxcore-log( 4951): 
W/jxcore-log( 4951): Process ARCH arm
W/jxcore-log( 4951): 
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_4747/cgroup.procs: No such file or directory
,E/SQLiteLog( 5184): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 5184): PlayLogger.onLoggerConnected
,I/jxcore-log( 4951): JXcore Cordova bridge is ready!
I/jxcore-log( 4951): 
,W/jxcore-log( 4951): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4951): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 4951): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4951): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4951): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 4951): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2473): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2473): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2473): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:305 vsyncs) (1:1061)
,D/OtaApp  ( 2473): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2473): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 4951): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1404): onFinishInput()
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:37000 mC
,I/SFPerfTracer(  280):      triggers: (rate: 15:525) (compose: 0:1) (post: 0:1) (render: 0:2) (14:993 frames) (15:1081)
D/SFPerfTracer(  280):        layers: (4:12) (FocusedStackFrame (0xb72f8c68): 0:16)* (DimLayer (0xb7383e80): 0:7) (StatusBar (0xb73a8e68): 15:172) (NavigationBar (0xb73aa0f8): 12:44) (com.android.systemui.ImageWallpaper (0xb73abfb0): 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb739f950): 0:52)- (Starting com.test.thalitest (0xb73af5e8): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb736da10): 15:59) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb73af5e8): 0:4)* 
,I/ActivityManager(  883): Killing 4909:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_4909/cgroup.procs: No such file or directory
,V/AlarmManager(  883): send {2d396c54, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  883): done {2d396c54, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [17ms]
,V/AlarmManager(  883): send {1d6ce7fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): done {1d6ce7fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [7ms]
,V/AlarmManager(  883): send {11445154, *alarm*:android.intent.action.TIME_TICK}
,I/ActivityManager(  883): Killing 4988:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_4988/cgroup.procs: No such file or directory
,V/AlarmManager(  883): done {11445154, *alarm*:android.intent.action.TIME_TICK} [78ms]
,D/CAR.SERVICE( 5097): mConnectedToCar = false, abort
,E/ActivityThread( 5097): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 5097): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 5097): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5097): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5097): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5097): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5097): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5097): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5097): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5097): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5097): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5097): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5097): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5097): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5097): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5097): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5097): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5097): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5097): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5097): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5097): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5097): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5097): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5097): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5097): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 5097): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 5097): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5097): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5097): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5097): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5097): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5097): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5097): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5097): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5097): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5097): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5097): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5097): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5097): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5097): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5097): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5097): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5097): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5097): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5097): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5097): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5097): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  883): Unbind failed: could not find connection for android.os.BinderProxy@20bc0cf2
,D/TaskPersister(  883): removeObsoleteFile: deleting file=8_task.xml
,W/ContextImpl( 5184): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5184): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  883): Killing 5097:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_5097/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:36000 mC
,V/AlarmManager(  883): send {84fbc9f, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  883): done {84fbc9f, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [12ms]
,D/Finsky  ( 4970): [565] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4970): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2473):  Nonce Reponse 
,I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:35000 mC
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=315, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311398, SEQNUM=4345, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-204, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311286, SEQNUM=4347, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-247, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  883): Explicit concurrent mark sweep GC freed 19413(1032KB) AllocSpace objects, 6(176KB) LOS objects, 33% free, 21MB/31MB, paused 1.810ms total 117.739ms
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 21245(1187KB) AllocSpace objects, 17(474KB) LOS objects, 39% free, 7MB/12MB, paused 797us total 44.264ms
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2473):  Nonce Reponse 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1404): run()
I/Keyboard.Facilitator( 1404): flushDynamicLanguageModels()
,I/ConfigService( 1704): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  883): send {ab640d8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  883): send {1d6ce7fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): done {ab640d8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,V/AlarmManager(  883): done {1d6ce7fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [11ms]
,V/AlarmManager(  883): send {11445154, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {11445154, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ConfigService( 1704): onDestroy
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  883): BstSensorExt: id=1598182242, en=0
D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  883): Display changed displayId=0
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb726f550
D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb877b820
,I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1200114376)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1200114376) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb877b820
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  883): Excessive delay in setPowerMode(): 321ms
,I/WindowManager(  883): AOD feature not enabled!
,I/PowerManagerService(  883): Sleeping (uid 1000)...
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  296): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  883): startHal
,E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e3189c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8711310, mCls = 0x101956
I/WifiNative-HAL(  883): Could not start hal
,D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 false
,E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 4
,I/Keyboard.Facilitator( 1404): onFinishInput()
D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  296): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  296): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  296): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  296): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e3189c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8711310, mCls = 0x201932
I/WifiNative-HAL(  883): Could not start hal
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  883): setSuspendOptimizations: 4 true
,E/WifiStateMachine(  883): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
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
,V/AlarmManager(  883): send {3ffaaf33, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  883): done {3ffaaf33, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311409, SEQNUM=4359, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-331, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  883): send {139052f0, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {139052f0, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,E/global frequency( 2473): no tags to log
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2473): Explicit concurrent mark sweep GC freed 15879(914KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 10MB/18MB, paused 1.231ms total 74.771ms
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1530): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1530): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 36909(1945KB) AllocSpace objects, 16(568KB) LOS objects, 39% free, 7MB/12MB, paused 558us total 33.811ms
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1530): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  883): Explicit concurrent mark sweep GC freed 11494(639KB) AllocSpace objects, 2(193KB) LOS objects, 33% free, 20MB/31MB, paused 1.730ms total 123.737ms
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2473): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2473): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2473): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2473): BcsDSCheckin.events found events 2000
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2473): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2473): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2473): unknown error code mapping for: 0
I/global frequency( 2473): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2473): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3533(139KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.314ms total 35.781ms
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2473):  Nonce Reponse 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2473): Explicit concurrent mark sweep GC freed 37149(2MB) AllocSpace objects, 6(148KB) LOS objects, 40% free, 11MB/18MB, paused 1.096ms total 71.726ms
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1704): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  883): send {ab640d8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): send {dbfae1c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  883): send {1d6ce7fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): done {ab640d8, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [9ms]
,V/AlarmManager(  883): done {dbfae1c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [12ms]
V/AlarmManager(  883): done {1d6ce7fd, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [12ms]
,I/ActivityManager(  883): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5317 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 5317): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5317): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5317): GMS http client unavailable, use old client
,I/ActivityManager(  883): Killing 5161:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_5161/cgroup.procs: No such file or directory
,I/VacuumService( 1704): Vacuum at: now=1457623559934 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1404): run()
I/Keyboard.Facilitator( 1404): flushDynamicLanguageModels()
,I/ConfigService( 1704): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1704): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311855, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-553, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  883): send {11445154, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {11445154, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311159, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-1054, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2473):  Nonce Reponse 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {11445154, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {2d396c54, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 4970): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  883): send {1387ae6a, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  883): done {1387ae6a, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [21ms]
,V/AlarmManager(  883): done {2d396c54, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [33ms]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  883): done {11445154, *alarm*:android.intent.action.TIME_TICK} [65ms]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4970): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4970): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4970): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4970): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  883): send {2973c5ae, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 4970): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,I/art     (  883): Explicit concurrent mark sweep GC freed 12919(602KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.315ms total 111.178ms
,D/DeviceConnectionService( 1704): client connected with version: 8296000
,D/WearableService( 1704): callingUid 10016, callindPid: 1704
,V/AlarmManager(  883): done {2973c5ae, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [130ms]
,D/Finsky  ( 4970): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/Finsky  ( 4970): [579] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4970): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4970): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {11445154, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {29a7a9d, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  883): done {29a7a9d, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [17ms]
,V/AlarmManager(  883): done {11445154, *alarm*:android.intent.action.TIME_TICK} [47ms]
,D/Finsky  ( 4970): [565] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4970): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311682, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-1371, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2473):  Nonce Reponse 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 36238(2MB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/21MB, paused 964us total 184.542ms
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7c79d6f)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14d00a7c)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17ae6f05)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1df6fb5a)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34515268)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@322bf681)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19cfcb67)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@61d2d14)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fa079bd)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11999bb2)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5436): 
D/AndroidRuntime( 5436): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5436): CheckJNI is OFF
D/AndroidRuntime( 5436): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10573 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 4951:com.test.thalitest/u0a573 (adj 11): stop com.test.thalitest
D/WifiService(  883): Client connection lost with reason: 4
W/PackageSettings(  883): Skipping PackageSetting{f36067b com.example.hello/10568} due to missing metadata
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10573 user=0: pkg removed
I/art     ( 2892): Explicit concurrent mark sweep GC freed 4031(871KB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 7MB/12MB, paused 546us total 34.872ms
W/ActivityManager(  883): Spurious death for ProcessRecord{1237b30e 4951:com.test.thalitest/u0a573}, curProc for 4951: null
W/GeofencerStateMachine( 1704): Ignoring removeGeofence because network location is disabled.
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1404): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1404): run()
I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5464 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Decoder ( 1404): createOrResetDecoder
I/art     ( 1558): Explicit concurrent mark sweep GC freed 3850(254KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 702us total 136.334ms
I/art     ( 1904): Explicit concurrent mark sweep GC freed 1053(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 895us total 147.664ms
I/art     (  883): Explicit concurrent mark sweep GC freed 10608(766KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 21MB/31MB, paused 3.609ms total 170.615ms
I/art     (  883): WaitForGcToComplete blocked for 144.524ms for cause Explicit
I/ConfigService( 1704): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1404): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1404): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1404): run()
I/StatsUtilsManager( 1404): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1404): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5464): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  883): Explicit concurrent mark sweep GC freed 6435(358KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 3.307ms total 175.694ms
I/ContactLocale( 5464): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5489 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  883): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=9_task_thumbnail.png
W/asset   ( 5489): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5489): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5489): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Launcher( 1558): Deferring update until onResume
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5507 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 5507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1904): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1904): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1904): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1904): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1904): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1904): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1904): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1704): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1704): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1904): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1904): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1904): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1904): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1904): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1904): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1904): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1904): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1904): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1904): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1904): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1904): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1904): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 5436): Shutting down VM
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5535 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  883): Killing 5129:com.android.providers.calendar/u0a5 (adj 15): empty #7
W/libprocessgroup(  883): failed to open /acct/uid_10005/pid_5129/cgroup.procs: No such file or directory
I/Icing   ( 1904): doRemovePackageData com.test.thalitest
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5562 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/SQLiteDatabase( 5317): Failed to open database '/data/user/0/com.google.android.gsf/databases/googlesettings.db'.
E/SQLiteDatabase( 5317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5317): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5317): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/SQLiteDatabase( 5317): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteDatabase( 5317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteDatabase( 5317): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 5317): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteOpenHelper( 5317): Couldn't open googlesettings.db for writing (will try read-only):
E/SQLiteOpenHelper( 5317): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 5317): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 5317): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5317): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5317): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/SQLiteOpenHelper( 5317): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteOpenHelper( 5317): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteOpenHelper( 5317): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper( 5317): 	at android.os.Binder.execTransact(Binder.java:446)
W/SQLiteOpenHelper( 5317): Opened googlesettings.db in read-only mode
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
