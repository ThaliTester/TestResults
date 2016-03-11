#### Test 62509094e6af764_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/UpdateIcingCorporaServi( 4392): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 4392): UpdateCorporaTask done [took 388 ms] updated apps [took 388 ms] 
--------- beginning of system
I/ActivityManager(  885): Killing 4143:com.motorola.context/u0a8 (adj 15): empty #7
I/ThermalEngine(  303): Sensor:xo_therm_pu2:37000 mC
D/AndroidRuntime( 4442): 
D/AndroidRuntime( 4442): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4442): CheckJNI is OFF
W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_4143/cgroup.procs: No such file or directory
I/Icing   ( 1950): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
I/GAv4    ( 4410): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4410):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4410):   adb logcat -s GAv4
W/GAv4    ( 4410): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Icing   ( 1950): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
W/GAv4    ( 4410): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4410): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/AndroidRuntime( 4442): Calling main entry com.android.commands.am.Am
W/AnalyticsTrackerProxyImpl( 4410): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (194 us)
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4442): Shutting down VM
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4473 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.204ms
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.348ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 366us total 23.475ms
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4410): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4495 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4256:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/ResourcesManager( 4410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  885): failed to open /acct/uid_10005/pid_4256/cgroup.procs: No such file or directory
,W/ResourcesManager( 4495): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 4410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/WebViewFactory( 4473): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/System  ( 4410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4410): Installed default security provider GmsCore_OpenSSL
,I/LibraryLoader( 4473): Time to load native libraries: 3 ms (timestamps 7267-7270)
,I/LibraryLoader( 4473): Expected native library version number "",actual native library version number ""
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 4473): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 4473): Expected native library version number "",actual native library version number ""
,I/chromium( 4473): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SFPerfTracer(  278):      triggers: (rate: 14:559) (compose: 0:1) (post: 0:1) (render: 0:2) (7:863 frames) (8:939)
D/SFPerfTracer(  278):        layers: (5:12) (FocusedStackFrame (0xb89ec310): 0:11)* (DimLayer (0xb8a7d398): 0:6) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8a7fa58): 0:30)- (StatusBar (0xb8a83600): 1:138) (NavigationBar (0xb8a9af00): 0:37) (com.android.systemui.ImageWallpaper (0xb8aa3dc0): 0:35)* (Starting com.motorola.ccc.ota (0xb8a54388): 0:27)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8aa61b0): 8:55) (Starting com.test.thalitest (0xb8a54388): 8:12) 
,I/BrowserStartupController( 4473): Initializing chromium process, singleProcess=true
,W/art     ( 4473): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4473): ApplicationContext is null in ApplicationStatus
,W/chromium( 4473): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4473): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4473): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4473): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4473): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4473): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4473): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4473): Local Branch: 
I/Adreno-EGL( 4473): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4473): Local Patches: NONE
I/Adreno-EGL( 4473): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Icing   ( 1950): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@247cd01d:true
,D/BluetoothAdapter( 4473): 446216149: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4538 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (39:227 vsyncs) (41:953)
,I/Icing   ( 1950): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,W/art     ( 4473): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 4538): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/AwContents( 4473): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4473): CordovaWebView is running on device made by: motorola
,W/art     ( 4473): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4473): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4473): Render dirty regions requested: true
,D/Atlas   ( 4473): Validating map...
,W/chromium( 4473): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4473): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4473): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1162
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +1s162ms
,D/Finsky  ( 4538): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4538): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4538): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4538): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4538): [1] Libraries$2.run: Finished loading 1 libraries.
E/Adreno-ES20( 4473): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4473): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/ActivityManager(  885): Killing 3565:com.android.defcontainer/u0a10 (adj 15): empty #7
,D/Ads     ( 4538): Skipping gmscore version check
,W/BindingManager( 4473): Cannot call determinedVisibility() - never saw a connection for the pid: 4473
,W/libprocessgroup(  885): failed to open /acct/uid_10010/pid_3565/cgroup.procs: No such file or directory
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/art     (  885): Explicit concurrent mark sweep GC freed 13151(645KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.927ms total 131.541ms
D/Finsky  ( 4538): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  885): Killing 4335:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/JsMessageQueue( 4473): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_4335/cgroup.procs: No such file or directory
,D/Finsky  ( 4538): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4538): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Adreno-ES20( 4473): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 4473): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 4473): JniHelper::setJavaVM(0xb8ece310), pthread_self() = -1188870728
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ae68ec added. We now have 1 listener(s)
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4473): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4473): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4473): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4473): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9da6bb added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4473): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  885): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4473): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4473): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4473): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4473): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4473): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 4473): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager(  885): send {a43a0f7, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  885): done {a43a0f7, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [3ms]
,D/Finsky  ( 4538): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4538): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4622 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4622): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4622): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Finsky  ( 4538): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 4622): VM with version 2.1.0 has multidex support
I/MultiDex( 4622): install
I/MultiDex( 4622): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4622): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4622): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4622): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4622): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1696): callingUid 10016, callindPid: 1696
,D/ChimeraCfgMgr( 4622): Reading stored module config
,D/LocationInitializer( 1950): Restart initialization of location,
,E/MDM     ( 1696): [158] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1696): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1696): No location to return for getLastLocation()
W/FusedLocationProvider( 1696): location=null
,D/ChimeraCfgMgr( 4622): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 2681): Explicit concurrent mark sweep GC freed 2680(105KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 355us total 29.111ms
,D/CAR.SERVICE( 4622): Connecting to CarCallService...
,I/art     ( 4622): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 4622): Install completed successfully. count=14 extracted=0
I/art     ( 4622): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 4622): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 4622): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 4622): Creating a new PhoneAdapter instance
,W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 4622): setListener: com.google.android.gms.car.dn@2305b52
W/ActivityManager(  885): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 4622): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 4622): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 4622): Package validated; name: com.android.vending
,V/Finsky  ( 4538): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4538): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4538): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  885): send {9472350, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 4538): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,V/AlarmManager(  885): done {9472350, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [22ms]
,D/Finsky  ( 4538): [481] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4538): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/DeviceConnectionService( 1696): client connected with version: 8296000
,D/Finsky  ( 4538): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4538): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Killing 4355:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/ActivityManager(  885): Killing 3786:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_4355/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4658 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_3786/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/ResourcesManager( 4658): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4658): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,W/jxcore-log( 4473): Initializing JXcore engine
W/jxcore-log( 4473): JXcore engine is ready
,W/Thread-465( 4617): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9314]" dev="sockfs" ino=9314 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-465( 4617): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-465( 4617): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6772]" dev="sockfs" ino=6772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-465( 4617): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[20757]" dev="sockfs" ino=20757 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4473): Starting JXcore engine
,W/jxcore-log( 4473): Platform android
W/jxcore-log( 4473): 
W/jxcore-log( 4473): Process ARCH arm
W/jxcore-log( 4473): 
,I/jxcore-log( 4473): JXcore Cordova bridge is ready!
I/jxcore-log( 4473): 
,W/jxcore-log( 4473): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4473): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 4473): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4473): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4473): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 4473): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/CalendarProvider2( 4658): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4658): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/OtaApp  ( 2441): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2441): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2441): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2441): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2441): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=4683 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2441): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2441): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2441): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  885): Killing 4392:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_4392/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {2c0caf1, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,W/ResourcesManager( 4683): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator( 1414): onFinishInput()
,W/IInputConnectionWrapper( 4473): showStatusIcon on inactive InputConnection
,V/AlarmManager(  885): done {2c0caf1, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [98ms]
,E/SQLiteLog( 4658): (284) automatic index on view_events(_id)
,I/ActivityManager(  885): Killing 4410:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_4410/cgroup.procs: No such file or directory
,I/SFPerfTracer(  278):      triggers: (rate: 14:560) (compose: 0:1) (post: 0:1) (render: 0:3) (8:949 frames) (9:1045)
,D/SFPerfTracer(  278):        layers: (5:12) (FocusedStackFrame (0xb89ec310): 0:16)* (DimLayer (0xb8a7d398): 0:9) (StatusBar (0xb8a83600): 4:157) (NavigationBar (0xb8a9af00): 0:50) (com.android.systemui.ImageWallpaper (0xb8aa3dc0): 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8aa61b0): 0:57)- (Starting com.test.thalitest (0xb8a54388): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a7fee0): 9:73) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8a539a8): 6:10) 
,I/ActivityManager(  885): Killing 4495:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_4495/cgroup.procs: No such file or directory
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (24:318 vsyncs) (26:1066)
,D/CAR.SERVICE( 4622): mConnectedToCar = false, abort
,E/ActivityThread( 4622): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 4622): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d0fe6fa that was originally bound here
E/ActivityThread( 4622): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 4622): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 4622): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 4622): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 4622): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4622): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4622): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4622): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 4622): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 4622): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 4622): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 4622): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 4622): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 4622): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 4622): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 4622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 4622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4622): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4622): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 4622): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4622): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 4622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 4622): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 4622): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37a1f3dd that was originally bound here
E/ActivityThread( 4622): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 4622): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 4622): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 4622): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 4622): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4622): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 4622): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 4622): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 4622): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 4622): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 4622): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 4622): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 4622): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 4622): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 4622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 4622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4622): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4622): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 4622): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4622): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 4622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  885): Unbind failed: could not find connection for android.os.BinderProxy@2d631aae
,D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:37000 mC
,V/AlarmManager(  885): send {15e7904f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {15e7904f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  885): send {daab3dc, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  885): done {daab3dc, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/ActivityManager(  885): Killing 4622:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/ActivityManager(  885): Killing 2681:com.google.process.gapps/u0a16 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_4622/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_2681/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {284a33ba, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  885): done {284a33ba, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,D/Finsky  ( 4538): [470] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4538): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:35000 mC
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2441):  Nonce Reponse 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: nonce.json
D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:35000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=312, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309540, SEQNUM=4336, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-77, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  885): send {27719d02, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {27719d02, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 20301(1146KB) AllocSpace objects, 16(461KB) LOS objects, 39% free, 7MB/12MB, paused 927us total 38.557ms
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2441):  Nonce Reponse 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=305, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310320, SEQNUM=4340, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-84, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2441): Explicit concurrent mark sweep GC freed 21492(1269KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 1.085ms total 131.163ms
,I/art     (  885): Explicit concurrent mark sweep GC freed 17980(908KB) AllocSpace objects, 6(176KB) LOS objects, 33% free, 21MB/31MB, paused 1.762ms total 120.036ms
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1414): run()
,I/Keyboard.Facilitator( 1414): flushDynamicLanguageModels()
,I/ConfigService( 1696): onCreate
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/ConfigService( 1696): onDestroy
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
,V/AlarmManager(  885): send {bdf3a47, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): send {daab3dc, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  885): done {bdf3a47, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [13ms]
,V/AlarmManager(  885): done {daab3dc, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [18ms]
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
,D/        (  885): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  885): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb896a550
D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  885): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  885): Display changed displayId=0
,I/rmt_storage(  288): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb818e820
,I/rmt_storage(  288): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  288): wakelock acquired: 1, error no: 42
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1206328008)
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  288): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1206328008) wakelock released: 1, error no: 0
I/rmt_storage(  288): 
,I/rmt_storage(  288): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb818e820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
D/SurfaceControl(  885): Excessive delay in setPowerMode(): 327ms
,I/WindowManager(  885): AOD feature not enabled!
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/PowerManagerService(  885): Sleeping (uid 1000)...
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  885): startHal
,E/wifi    (  885): getStaticLongField sWifiHalHandle 0xa2e7a89c
D/wifi    (  885): halHandle = 0x0, mVM = 0xb8ece310, mCls = 0x18e2
I/WifiNative-HAL(  885): Could not start hal
D/WifiStateMachine(  885): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: true
E/WifiStateMachine(  885): setSuspendOptimizations: 4 false
E/WifiStateMachine(  885): mSuspendOptNeedsDisabled 4
,I/Keyboard.Facilitator( 1414): onFinishInput()
D/        (  885): activate, handle: 1598182229, enabled: 0, index 0
E/        (  885): <BST> disable accel, orig state: 1
I/        (  885): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  885): startHal
E/wifi    (  885): getStaticLongField sWifiHalHandle 0xa2e7a89c
D/wifi    (  885): halHandle = 0x0, mVM = 0xb8ece310, mCls = 0x1018aa
I/WifiNative-HAL(  885): Could not start hal
D/WifiStateMachine(  885): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  885): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  885): setSuspendOptimizations: 4 true
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  885): mSuspendOptNeedsDisabled 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  885): send {27a18b5e, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  885): done {27a18b5e, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310770, SEQNUM=4351, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13120, POWER_SUPPLY_CHARGE_COUNTER=-181, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  885): send {bdf3a47, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {bdf3a47, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,V/AlarmManager(  885): send {27719d02, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {f32b3f, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {f32b3f, *walarm*:com.google.android.intent.action.SEND_IDLE} [10ms]
,V/AlarmManager(  885): done {27719d02, *alarm*:android.intent.action.TIME_TICK} [38ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,E/global frequency( 2441): no tags to log
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2441): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2441): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2441): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2441): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 36790(1935KB) AllocSpace objects, 16(564KB) LOS objects, 39% free, 7MB/12MB, paused 719us total 33.039ms
,D/BSUtils ( 2441): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2441): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2441): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2441): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2441): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2441): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2441): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2441): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2441): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2441): BcsDSCheckin.events found events 2000
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/MotorolaSettings( 2441): no such table to get this name = privacy_droid_blast
W/System.err( 2441): java.lang.Exception
W/System.err( 2441): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
W/System.err( 2441): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 2441): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2441): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2441): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 2441): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 2441): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsCore.limitRuleExceeded(BcsCore.java:810)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsCore.doCallHomeCore(BcsCore.java:592)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsCore.doCallHome(BcsCore.java:494)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:325)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:383)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 2441): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 2441): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 2441): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 2441): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 2441): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 2441): 	at java.lang.Thread.run(Thread.java:818)
I/global frequency( 2441): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2441): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2441): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 2441): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 2441): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2441): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 2441): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/BSUtils ( 2441): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     (  885): Explicit concurrent mark sweep GC freed 13881(780KB) AllocSpace objects, 2(192KB) LOS objects, 33% free, 20MB/31MB, paused 1.675ms total 111.807ms
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 3576(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 683us total 31.161ms
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2441): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2441): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 2441): unknown error code mapping for: 0
I/global frequency( 2441): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2441): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2441): Explicit concurrent mark sweep GC freed 39740(3MB) AllocSpace objects, 7(164KB) LOS objects, 40% free, 11MB/18MB, paused 1.061ms total 65.354ms
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2441):  Nonce Reponse 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1696): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  885): send {1e793c5b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  885): send {daab3dc, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  885): send {bdf3a47, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {1e793c5b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,V/AlarmManager(  885): done {daab3dc, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [7ms]
,V/AlarmManager(  885): done {bdf3a47, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [14ms]
,I/VacuumService( 1696): Vacuum at: now=1457695349198 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1414): run()
I/Keyboard.Facilitator( 1414): flushDynamicLanguageModels()
,I/ConfigService( 1696): onCreate
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1696): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311221, SEQNUM=4357, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10917, POWER_SUPPLY_CHARGE_COUNTER=-416, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  885): send {27719d02, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {27719d02, *alarm*:android.intent.action.TIME_TICK} [101ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2441):  Nonce Reponse 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310520, SEQNUM=4359, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-896, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  885): send {27719d02, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {15e7904f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 4538): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  885): send {a43a0f7, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  885): done {a43a0f7, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [20ms]
,V/AlarmManager(  885): done {15e7904f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [28ms]
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): done {27719d02, *alarm*:android.intent.action.TIME_TICK} [65ms]
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4538): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4538): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4538): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4538): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  885): send {1700c61e, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 4538): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1696): client connected with version: 8296000
,D/WearableService( 1696): callingUid 10016, callindPid: 1696
,V/AlarmManager(  885): done {1700c61e, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [24ms]
,D/Finsky  ( 4538): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 4538): [485] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4538): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4538): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {6eabfcd, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  885): done {6eabfcd, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,D/Finsky  ( 4538): [470] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4538): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309881, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1614, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309585, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=504, POWER_SUPPLY_CHARGE_COUNTER=4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310763, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  885): Explicit concurrent mark sweep GC freed 15179(727KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.796ms total 114.518ms
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2441):  Nonce Reponse 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2441): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2441): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2441): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2441): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2441): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2441): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2441): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310439, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-55, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,TIME-OUT KILL (timeout was 1400000ms),I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 4886): 
D/AndroidRuntime( 4886): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4886): CheckJNI is OFF
D/AndroidRuntime( 4886): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 4473:com.test.thalitest/u0a109 (adj 11): stop com.test.thalitest
D/WifiService(  885): Client connection lost with reason: 4
W/ActivityManager(  885): Spurious death for ProcessRecord{2e6dab7e 4473:com.test.thalitest/u0a109}, curProc for 4473: null
W/PackageSettings(  885): Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
I/art     ( 2877): Explicit concurrent mark sweep GC freed 4616(1022KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 7MB/12MB, paused 712us total 26.021ms
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1696): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
I/art     ( 1563): Explicit concurrent mark sweep GC freed 5696(399KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 504us total 95.310ms
I/Decoder ( 1414): createOrResetDecoder
I/art     ( 1950): Explicit concurrent mark sweep GC freed 941(41KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 13MB/18MB, paused 804us total 128.552ms
D/VoicemailCleanupService( 1624): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4918 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  885): Explicit concurrent mark sweep GC freed 10016(809KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/31MB, paused 1.696ms total 141.432ms
I/art     (  885): WaitForGcToComplete blocked for 59.457ms for cause Explicit
I/ConfigService( 1696): onCreate
W/asset   ( 4918): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 4918): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4918): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4939 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Launcher( 1563): Deferring update until onResume
I/art     (  885): Explicit concurrent mark sweep GC freed 4424(213KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 5.190ms total 210.976ms
D/AndroidRuntime( 4886): Shutting down VM
W/ContextImpl( 4939): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1950): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1950): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1696): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1696): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4964 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 1950): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1950): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1950): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1950): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1950): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1950): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1950): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1950): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1950): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1950): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1950): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1950): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1950): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1950): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  885): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=4985 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
W/Launcher( 1563): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5004 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/GservicesProvider( 4985): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 4985): GMS http client unavailable, use old client
I/GoogleHttpClient( 4985): GMS http client unavailable, use old client
E/SQLiteDatabase( 4985): Failed to open database '/data/user/0/com.google.android.gsf/databases/googlesettings.db'.
E/SQLiteDatabase( 4985): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4985): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 4985): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4985): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/SQLiteDatabase( 4985): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteDatabase( 4985): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteDatabase( 4985): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4985): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteOpenHelper( 4985): Couldn't open googlesettings.db for writing (will try read-only):
E/SQLiteOpenHelper( 4985): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4985): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 4985): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4985): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/SQLiteOpenHelper( 4985): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteOpenHelper( 4985): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteOpenHelper( 4985): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper( 4985): 	at android.os.Binder.execTransact(Binder.java:446)
W/SQLiteOpenHelper( 4985): Opened googlesettings.db in read-only mode
E/SQLiteDatabase( 4985): Failed to open database '/data/user/0/com.google.android.gsf/databases/subscribedfeeds.db'.
E/SQLiteDatabase( 4985): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4985): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 4985): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4985): 	at com.google.android.gsf.subscribedfeeds.AbstractSyncableContentProvider$1.onAccountsUpdated(AbstractSyncableContentProvider.java:174)
E/SQLiteDatabase( 4985): 	at android.accounts.AccountManager$15.run(AccountManager.java:1600)
E/SQLiteDatabase( 4985): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 4985): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4985): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4985): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/SQLiteDatabase( 4985): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4985): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4985): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/SQLiteDatabase( 4985): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AccountManager( 4985): Can't update accounts
E/AccountManager( 4985): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AccountManager( 4985): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AccountManager( 4985): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AccountManager( 4985): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AccountManager( 4985): 	at com.google.android.gsf.subscribedfeeds.AbstractSyncableContentProvider$1.onAccountsUpdated(AbstractSyncableContentProvider.java:174)
E/AccountManager( 4985): 	at android.accounts.AccountManager$15.run(AccountManager.java:1600)
E/AccountManager( 4985): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AccountManager( 4985): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AccountManager( 4985): 	at android.os.Looper.loop(Looper.java:135)
E/AccountManager( 4985): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AccountManager( 4985): 	at java.lang.reflect.Method.invoke(Native Method)
E/AccountManager( 4985): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AccountManager( 4985): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AccountManager( 4985): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
