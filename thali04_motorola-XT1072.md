#### Test 62509094aba5909_thali04_motorola-XT1072 Logs


```
--------- beginning of system
W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_4474/cgroup.procs: No such file or directory
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4935 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,--------- beginning of main
I/UpdateIcingCorporaServi( 4894): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  881): Waited long enough for: ServiceRecord{259ca0bf u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
D/AndroidRuntime( 4956): 
D/AndroidRuntime( 4956): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4956): CheckJNI is OFF
I/GAv4    ( 4935): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4935):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4935):   adb logcat -s GAv4
W/GAv4    ( 4935): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/UpdateIcingCorporaServi( 4894): UpdateCorporaTask done [took 195 ms] updated apps [took 195 ms] 
W/GAv4    ( 4935): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4935): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4935): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
D/AndroidRuntime( 4956): Calling main entry com.android.commands.am.Am
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 4935): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4935): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4995 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 3542:com.android.defcontainer/u0a10 (adj 15): empty #7
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (187 us)
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4956): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10010/pid_3542/cgroup.procs: No such file or directory
I/Icing   ( 1939): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5015 uid=10576 gids={50576, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 2575): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2575): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2575): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2575): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2575): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2575): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2575): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2575): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2575): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/CalendarProvider2( 4911): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4911): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/ResourcesManager( 4995): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 4935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  881): Activity reported stop, but no longer stopping: ActivityRecord{28ff078a u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
I/Icing   ( 1939): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
I/ActivityManager(  881): Killing 4785:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/System  ( 4935): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4935): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_4785/cgroup.procs: No such file or directory
,V/AlarmManager(  881): send {deef5c6, *alarm*:android.intent.action.TIME_TICK}
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  881): done {deef5c6, *alarm*:android.intent.action.TIME_TICK} [104ms]
,I/WebViewFactory( 5015): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5015): Time to load native libraries: 3 ms (timestamps 548-551)
,I/LibraryLoader( 5015): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5015): Binding Chromium to main looper Looper (main, tid 1) {2f1cd5f3}
,I/LibraryLoader( 5015): Expected native library version number "",actual native library version number ""
,I/chromium( 5015): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5015): Initializing chromium process, singleProcess=true
W/art     ( 5015): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5015): ApplicationContext is null in ApplicationStatus
,W/chromium( 5015): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5053 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1939): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/art     (  326): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 21.204ms
,W/chromium( 5015): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5015): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5015): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5015): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5015): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5015): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5015): Local Branch: 
I/Adreno-EGL( 5015): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5015): Local Patches: NONE
I/Adreno-EGL( 5015): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 359us total 20.719ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.965ms
,I/ActivityManager(  881): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5078 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d614295:true
,D/BluetoothAdapter( 5015): 858054223: getState() :  mService = null. Returning STATE_OFF
,I/GservicesProvider( 5078): Gservices pushing to system: true; secure/global: true
,I/Icing   ( 1939): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/GoogleHttpClient( 5078): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5078): GMS http client unavailable, use old client
,W/art     ( 5015): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5015): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  881): Killing 4836:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/SystemWebViewEngine( 5015): CordovaWebView is running on device made by: motorola
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_4836/cgroup.procs: No such file or directory,
,W/art     ( 5015): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5015): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 5053): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/OpenGLRenderer( 5015): Render dirty regions requested: true
,D/Atlas   ( 5015): Validating map...
,W/chromium( 5015): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  881): Explicit concurrent mark sweep GC freed 14735(738KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.051ms total 130.115ms
,I/OpenGLRenderer( 5015): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5015): Enabling debug mode 0
D/Finsky  ( 5053): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5053): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5053): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1359
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s359ms
,I/Keyboard.Facilitator( 1408): onFinishInput()
,D/Finsky  ( 5053): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5053): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5053): Skipping gmscore version check
,E/Adreno-ES20( 5015): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5015): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5151 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/BindingManager( 5015): Cannot call determinedVisibility() - never saw a connection for the pid: 5015
D/Finsky  ( 5053): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  881): Killing 4859:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_4859/cgroup.procs: No such file or directory
,D/Finsky  ( 5053): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,W/ResourcesManager( 5151): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Finsky  ( 5053): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 4894:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_4894/cgroup.procs: No such file or directory
,D/JsMessageQueue( 5015): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  881): Killing 4911:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (18:252 vsyncs) (20:1047)
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_4911/cgroup.procs: No such file or directory
,E/Adreno-ES20( 5015): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5015): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5015): JniHelper::setJavaVM(0xb87c8310), pthread_self() = -1196009824
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f6863c added. We now have 1 listener(s)
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5015): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5015): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5015): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5015): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3931204b added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5015): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5015): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
D/WifiService(  881): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5015): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5015): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5015): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5015): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,D/Finsky  ( 5053): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  881): send {253a11e8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  881): done {253a11e8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [17ms]
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/chromium( 5015): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Finsky  ( 5053): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5188 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5053): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 5188): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5188): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5188): VM with version 2.1.0 has multidex support
,I/MultiDex( 5188): install
I/MultiDex( 5188): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5188): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5188): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5188): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d6f7627: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5188): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1723): callingUid 10016, callindPid: 1723
D/ChimeraCfgMgr( 5188): Reading stored module config
,E/MDM     ( 1723): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1723): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1939): Restart initialization of location
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5188): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1723): No location to return for getLastLocation()
,W/FusedLocationProvider( 1723): location=null
,D/CAR.SERVICE( 5188): Connecting to CarCallService...
,I/art     ( 5188): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5188): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5188): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5188): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5188): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5188): Creating a new PhoneAdapter instance
,W/ActivityManager(  881): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5188): setListener: com.google.android.gms.car.dn@2556ff22
W/ActivityManager(  881): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5188): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5188): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5188): Package validated; name: com.android.vending
,V/Finsky  ( 5053): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5053): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5053): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  881): send {7545935, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5053): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,V/AlarmManager(  881): done {7545935, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [20ms]
,D/DeviceConnectionService( 1723): client connected with version: 8296000
,D/Finsky  ( 5053): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5053): [580] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5053): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5053): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Killing 4935:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/ActivityManager(  881): Killing 4205:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_4935/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_4205/cgroup.procs: No such file or directory
D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/jxcore-log( 5015): Initializing JXcore engine
W/jxcore-log( 5015): JXcore engine is ready
,W/Thread-569( 5179): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10576 path="socket:[5842]" dev="sockfs" ino=5842 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-569( 5179): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10576 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-569( 5179): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10576 path="socket:[7468]" dev="sockfs" ino=7468 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-569( 5179): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10576 path="socket:[22985]" dev="sockfs" ino=22985 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5015): Starting JXcore engine
,V/AlarmManager(  881): send {389f5022, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/ActivityManager(  881): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5226 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 5015): Platform android
W/jxcore-log( 5015): 
,W/jxcore-log( 5015): Process ARCH arm
W/jxcore-log( 5015): 
,W/ResourcesManager( 5226): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5226): Created com.android.providers.calendar.CalendarAlarmManager@2e6f1644(com.android.providers.calendar.CalendarProvider2@1aad632d)
,V/AlarmManager(  881): done {389f5022, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [160ms]
,E/SQLiteLog( 5226): (284) automatic index on view_events(_id)
,I/SFPerfTracer(  280):      triggers: (rate: 13:467) (compose: 0:1) (post: 0:1) (render: 0:2) (15:997 frames) (16:1084)
,D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb78f7690): 0:14)* (DimLayer (0xb7908e58): 0:6)* (StatusBar (0xb791bdf0): 0:159) (NavigationBar (0xb791d080): 0:35) (com.android.systemui.ImageWallpaper (0xb791ed98): 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7912900): 0:55)- (Starting com.test.thalitest (0xb78bba98): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb78d7748): 16:51) 
,I/jxcore-log( 5015): JXcore Cordova bridge is ready!
I/jxcore-log( 5015): 
,W/jxcore-log( 5015): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5015): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5015): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5015): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5015): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5015): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2575): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2575): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2575): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2575): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2575): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2575): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2575): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1408): onFinishInput()
W/IInputConnectionWrapper( 5015): showStatusIcon on inactive InputConnection
,I/CalendarProvider2( 5226): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5226): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  881): Killing 4809:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_4809/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 4995:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_4995/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:37000 mC
,V/AlarmManager(  881): send {19a005d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): done {19a005d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,D/CAR.SERVICE( 5188): mConnectedToCar = false, abort
,E/ActivityThread( 5188): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1de320ca that was originally bound here
E/ActivityThread( 5188): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1de320ca that was originally bound here
E/ActivityThread( 5188): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5188): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5188): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5188): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5188): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5188): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5188): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5188): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5188): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5188): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5188): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5188): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5188): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5188): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5188): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5188): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5188): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5188): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5188): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5188): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@f9084ed that was originally bound here
E/ActivityThread( 5188): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@f9084ed that was originally bound here
E/ActivityThread( 5188): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5188): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5188): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5188): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5188): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5188): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5188): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5188): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5188): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5188): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5188): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5188): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5188): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5188): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5188): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5188): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5188): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5188): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  881): Unbind failed: could not find connection for android.os.BinderProxy@3d54a6a3
,V/AlarmManager(  881): send {2ce2cda0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  881): done {2ce2cda0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task.xml
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=324, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310516, SEQNUM=4348, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-27243, POWER_SUPPLY_CHARGE_COUNTER=-400, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ActivityManager(  881): Killing 5188:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/ActivityManager(  881): Killing 5078:com.google.process.gapps/u0a16 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_5188/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_5078/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:35000 mC
,V/AlarmManager(  881): send {bd4ad1e, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  881): done {bd4ad1e, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [12ms]
,D/Finsky  ( 5053): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5053): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2575):  Nonce Reponse 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:34000 mC
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=304, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311075, SEQNUM=4352, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-25540, POWER_SUPPLY_CHARGE_COUNTER=-541, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=296, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310072, SEQNUM=4354, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-25040, POWER_SUPPLY_CHARGE_COUNTER=-636, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 20823(1180KB) AllocSpace objects, 17(477KB) LOS objects, 39% free, 7MB/12MB, paused 910us total 41.823ms
,I/art     (  881): Explicit concurrent mark sweep GC freed 20221(1085KB) AllocSpace objects, 6(177KB) LOS objects, 33% free, 21MB/31MB, paused 1.505ms total 120.605ms
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2575):  Nonce Reponse 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  881): send {deef5c6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {deef5c6, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1408): run()
,I/Keyboard.Facilitator( 1408): flushDynamicLanguageModels()
,I/ConfigService( 1723): onCreate
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  881): send {19e6471b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): send {2ce2cda0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  881): done {19e6471b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8ms]
,V/AlarmManager(  881): done {2ce2cda0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [11ms]
,I/ConfigService( 1723): onDestroy
,I/PowerManagerService(  881): Nap time (uid 1000)...
I/PowerManagerService(  881): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  881): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  881): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  881): Build Date: 10/28/14 Tue
I/Adreno-EGL(  881): Local Branch: 
I/Adreno-EGL(  881): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  881): Local Patches: NONE
I/Adreno-EGL(  881): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:331 vsyncs) (1:1148)
,D/        (  881): activate, handle: 1598182242, enabled: 0, index 2
D/        (  881): BstSensorExt: id=1598182242, en=0
D/        (  881): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  881): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  881): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb77e2550
,D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,V/ActivityManager(  881): Display changed displayId=0
,I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb846f820
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203309256)
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203309256) wakelock released: 1, error no: 0
I/rmt_storage(  302): 
,I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb846f820
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  881): Excessive delay in setPowerMode(): 326ms
,I/PowerManagerService(  881): Sleeping (uid 1000)...
,I/WindowManager(  881): AOD feature not enabled!
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  312): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  312): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  312): platform_set_parameters: exit with code(0)
E/msm8974_platform(  312): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
,D/audio_hw_extn(  312): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  312): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e3589c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb87c8310, mCls = 0x201a0a
I/WifiNative-HAL(  881): Could not start hal
D/WifiStateMachine(  881): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 false
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 4
,D/        (  881): activate, handle: 1598182229, enabled: 0, index 0
E/        (  881): <BST> disable accel, orig state: 1
I/        (  881): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
I/WifiNative-HAL(  881): startHal
,E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e3589c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb87c8310, mCls = 0x20197a
I/WifiNative-HAL(  881): Could not start hal
D/WifiStateMachine(  881): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: false
D/audio_hw_primary(  312): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  312): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  312): platform_set_parameters: exit with code(0)
,D/audio_hw_extn(  312): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  312): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 true
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 0
,I/Keyboard.Facilitator( 1408): onFinishInput()
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  881): send {3ad18782, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  881): done {3ad18782, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [11ms]
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310471, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14623, POWER_SUPPLY_CHARGE_COUNTER=-865, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  881): send {330c7e93, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {330c7e93, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,E/global frequency( 2575): no tags to log
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2575): Explicit concurrent mark sweep GC freed 22958(1399KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 1.236ms total 64.797ms
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 37545(2021KB) AllocSpace objects, 16(574KB) LOS objects, 39% free, 7MB/12MB, paused 848us total 38.475ms
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  881): Explicit concurrent mark sweep GC freed 12367(698KB) AllocSpace objects, 2(194KB) LOS objects, 33% free, 20MB/31MB, paused 1.445ms total 128.325ms
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2575): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2575): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2575): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2575): BcsDSCheckin.events found events 2000
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3525(139KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 578us total 26.789ms
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2575):  Nonce Reponse 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2575): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2575): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2575): unknown error code mapping for: 0
I/global frequency( 2575): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1723): disconnect managed GoogleApiClient
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  881): send {deef5c6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {e7670ef, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): send {2ce2cda0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  881): send {19e6471b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): done {e7670ef, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [13ms]
,V/AlarmManager(  881): done {2ce2cda0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [21ms]
V/AlarmManager(  881): done {19e6471b, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [21ms]
,V/AlarmManager(  881): done {deef5c6, *alarm*:android.intent.action.TIME_TICK} [55ms]
,I/ActivityManager(  881): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5346 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 5346): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5346): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5346): GMS http client unavailable, use old client
,I/ActivityManager(  881): Killing 5151:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_5151/cgroup.procs: No such file or directory
,I/VacuumService( 1723): Vacuum at: now=1457686688386 tag=VacuumService
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310977, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14623, POWER_SUPPLY_CHARGE_COUNTER=-1007, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1408): run()
I/Keyboard.Facilitator( 1408): flushDynamicLanguageModels()
,I/ConfigService( 1723): onCreate
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1723): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310243, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16927, POWER_SUPPLY_CHARGE_COUNTER=-1503, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {deef5c6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {deef5c6, *alarm*:android.intent.action.TIME_TICK} [105ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2575):  Nonce Reponse 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2575): Explicit concurrent mark sweep GC freed 39032(3MB) AllocSpace objects, 6(148KB) LOS objects, 40% free, 11MB/18MB, paused 1.194ms total 148.012ms
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {deef5c6, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {19a005d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 5053): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  881): send {253a11e8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  881): done {253a11e8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [29ms]
V/AlarmManager(  881): done {19a005d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [29ms]
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  881): done {deef5c6, *alarm*:android.intent.action.TIME_TICK} [65ms]
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5053): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5053): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5053): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,I/art     (  881): Explicit concurrent mark sweep GC freed 13043(600KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.446ms total 131.999ms
,D/Finsky  ( 5053): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  881): send {2abd20bc, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5053): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1723): client connected with version: 8296000
,D/Finsky  ( 5053): [584] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/WearableService( 1723): callingUid 10016, callindPid: 1723
,V/AlarmManager(  881): done {2abd20bc, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [21ms]
,D/Finsky  ( 5053): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5053): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5053): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {1d0f9a43, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  881): done {1d0f9a43, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,D/Finsky  ( 5053): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5053): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ClearcutLoggerApiImpl( 1723): disconnect managed GoogleApiClient
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310122, SEQNUM=4392, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-3638, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2575):  Nonce Reponse 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2575): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2575): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3406(148KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 713us total 29.595ms
,D/MMApiWebService( 2575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2575): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2575): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2575): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34e90417)
E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@73ff004)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@387299ed)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2dfff022)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d6fcab3)
,I/art     ( 1723): Explicit concurrent mark sweep GC freed 37658(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/21MB, paused 1.184ms total 153.042ms
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21ce0870)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1950ec6e)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1de33b9c)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c9219a5)
,E/DataBuffer( 1723): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@38a3617a)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5445): 
D/AndroidRuntime( 5445): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5445): CheckJNI is OFF
D/AndroidRuntime( 5445): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10576 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5015:com.test.thalitest/u0a576 (adj 11): stop com.test.thalitest
D/WifiService(  881): Client connection lost with reason: 4
W/PackageSettings(  881): Skipping PackageSetting{aa5900b com.example.hello/10568} due to missing metadata
W/ActivityManager(  881): Spurious death for ProcessRecord{29cfad1c 5015:com.test.thalitest/u0a576}, curProc for 5015: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10576 user=0: pkg removed
I/art     ( 2976): Explicit concurrent mark sweep GC freed 4251(955KB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 7MB/12MB, paused 593us total 35.708ms
I/art     ( 1557): Explicit concurrent mark sweep GC freed 7532(544KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 473us total 67.766ms
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1723): Ignoring removeGeofence because network location is disabled.
I/art     ( 1939): Explicit concurrent mark sweep GC freed 1900(79KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 865us total 128.891ms
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5473 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
I/Decoder ( 1408): createOrResetDecoder
I/ConfigService( 1723): onCreate
I/art     (  881): Explicit concurrent mark sweep GC freed 11417(823KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 21MB/31MB, paused 1.526ms total 190.669ms
I/art     (  881): WaitForGcToComplete blocked for 139.978ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5473): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5496 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/art     (  881): Explicit concurrent mark sweep GC freed 6026(324KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 2.197ms total 162.153ms
I/ContactLocale( 5473): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/asset   ( 5496): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5496): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5496): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5496): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/AndroidRuntime( 5445): Shutting down VM
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5517 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 5226:com.android.providers.calendar/u0a5 (adj 15): empty #7
I/Launcher( 1557): Deferring update until onResume
W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_5226/cgroup.procs: No such file or directory
W/ContextImpl( 5517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1939): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1723): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1723): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5543 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1939): doRemovePackageData com.test.thalitest
W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@288e9dc new=com.google.android.velvet.VelvetApplication@288e9dc
E/SQLiteLog( 1557): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
